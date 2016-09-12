#### Test 846390990f494e6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,09-12 08:25:32.199  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 08:25:32.221  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 08:25:32.227  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 08:25:32.282  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 08:25:32.282  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 08:25:32.282  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:25:32.282  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 08:25:32.300  3686  3686 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 08:25:32.301  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 08:25:32.301  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 08:25:32.826  3982  3982 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 08:25:32.830  3982  3982 D AndroidRuntime: CheckJNI is OFF
09-12 08:25:32.866  3982  3982 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 08:25:32.909  3982  3982 I Radio-JNI: register_android_hardware_Radio DONE
09-12 08:25:32.929  3982  3982 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 08:25:32.940   872  1968 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 08:25:32.993  2027  2445 W SearchService: Abort, client detached.
09-12 08:25:33.005  3982  3982 D AndroidRuntime: Shutting down VM
09-12 08:25:33.011  2027  2337 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fa4a400
09-12 08:25:33.012  2027  2027 I HotwordDetector: Closing mic
09-12 08:25:33.012  2027  2354 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 08:25:33.041   872   882 I ActivityManager: Start proc 3993:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 08:25:33.075   375  2356 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 08:25:33.077   375  2356 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 08:25:33.086   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 08:25:33.090  2027  2353 I MicroRecognitionRnrImpl: Detection finished
09-12 08:25:33.092  2027  2346 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 08:25:33.165  3993  3993 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 08:25:33.194  3993  3993 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 08:25:33.203  3993  3993 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9903-9906)
09-12 08:25:33.203  3993  3993 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 08:25:33.220  3993  3993 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b87ece8}
09-12 08:25:33.221  3993  3993 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 08:25:33.221  3993  3993 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 08:25:33.230  3993  3993 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 08:25:33.232  3993  3993 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 08:25:33.251  3993  3993 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 08:25:33.261  3993  3993 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 08:25:33.261  3993  3993 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 08:25:33.261  3993  3993 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 08:25:33.261  3993  3993 I Adreno  : Build Date                       : 10/20/15
09-12 08:25:33.261  3993  3993 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 08:25:33.261  3993  3993 I Adreno  : Local Branch                     : M14
09-12 08:25:33.261  3993  3993 I Adreno  : Remote Branch                    : 
09-12 08:25:33.261  3993  3993 I Adreno  : Remote Branch                    : 
09-12 08:25:33.261  3993  3993 I Adreno  : Reconstruct Branch               : 
,09-12 08:25:33.322   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@743cb78:true
,09-12 08:25:33.395  3993  3993 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 08:25:33.409  3993  3993 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 08:25:33.490  3993  4032 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 08:25:33.505  3993  4018 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 08:25:33.549  3993  4032 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 08:25:33.627   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +600ms
,09-12 08:25:33.629  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-12 08:25:33.763  3993  3993 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3993
,09-12 08:25:33.884   872  1994 I ActivityManager: Killing 3383:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 08:25:33.928   872  1994 I ActivityManager: Killing 3610:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-12 08:25:33.928  3993  3993 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 08:25:34.114  3993  4034 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1699612368
,09-12 08:25:34.122  3993  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 08:25:34.122  3993  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 08:25:34.122  3993  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 08:25:34.122  3993  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 08:25:34.122  3993  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 08:25:34.123  3993  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a309f added. We now have 1 listener(s)
,09-12 08:25:34.126  3993  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 08:25:34.127  3993  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 08:25:34.128  3993  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:25:34.128  3993  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 08:25:34.135  3993  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4704c4a added. We now have 1 listener(s)
,09-12 08:25:34.136  3993  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:25:34.141   872  1308 D WifiService: New client listening to asynchronous messages
,09-12 08:25:34.142  3993  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 08:25:34.142  3993  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 08:25:34.142  3993  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 08:25:34.143  3993  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 08:25:34.143  3993  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 08:25:34.148  3993  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 08:25:34.148  3993  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 08:25:34.158  3993  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:34.158  3993  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 08:25:34.158  3993  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 08:25:34.158  3993  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 08:25:34.160  3993  4034 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 08:25:34.160  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:34.162  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:34.352  3993  3993 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 08:25:34.706  3993  4003 I art     : Background sticky concurrent mark sweep GC freed 71489(6MB) AllocSpace objects, 18(1604KB) LOS objects, 29% free, 23MB/32MB, paused 910us total 133.354ms
,09-12 08:25:35.216  3993  4042 W jxcore-log: Initializing JXcore engine
,09-12 08:25:35.216  3993  4042 W jxcore-log: JXcore engine is ready
,09-12 08:25:35.273  4042  4042 W Thread-373: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 08:25:35.276  4042  4042 W Thread-373: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11530]" dev="sockfs" ino=11530 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 08:25:35.276  4042  4042 W Thread-373: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 08:25:35.276  4042  4042 W Thread-373: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26144]" dev="sockfs" ino=26144 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 08:25:35.298  3993  4042 W jxcore-log: Starting JXcore engine
,09-12 08:25:35.431  3993  4042 W jxcore-log: Platform android
09-12 08:25:35.431  3993  4042 W jxcore-log: 
,09-12 08:25:35.431  3993  4042 W jxcore-log: Process ARCH arm
09-12 08:25:35.431  3993  4042 W jxcore-log: 
,09-12 08:25:35.492   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 08:25:35.704  3993  4042 I jxcore-log: JXcore Cordova bridge is ready!
09-12 08:25:35.704  3993  4042 I jxcore-log: 
,09-12 08:25:35.705  3993  4042 W jxcore-log: JXcore engine is started
,09-12 08:25:35.712  3993  4034 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 08:25:35.717  3993  3993 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 08:25:35.799   872  1892 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:25:45.319  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 08:25:45.319  3993  4042 I jxcore-log: 
,09-12 08:25:45.321  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 08:25:45.321  3993  4042 I jxcore-log: 
,09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:45.330  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:25:45.332  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:25:45.335  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 08:25:45.335  3993  4042 I jxcore-log: 
,09-12 08:25:45.337  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 08:25:45.337  3993  4042 I jxcore-log: 
,09-12 08:25:45.833  3993  4042 D executeNativeTests: Running unit tests
,09-12 08:25:45.891  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 08:25:45.891  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc added. We now have 2 listener(s)
,09-12 08:25:45.893  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 08:25:45.893  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 08:25:45.893  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 08:25:45.893  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:25:45.893  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 added. We now have 2 listener(s)
09-12 08:25:45.893  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:25:45.894  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 08:25:45.900  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:45.907  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:25:45.908  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:45.908  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 08:25:45.911  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 08:25:45.912  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 08:25:45.913  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 08:25:45.914  3993  4042 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 08:25:45.914  3993  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 08:25:45.914  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 08:25:45.914  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 08:25:45.914  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 08:25:45.915  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:45.915  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:45.915  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:45.915  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:45.916  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:45.916  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 08:25:45.916  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:45.916  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:25:45.919  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc removed from the list
,09-12 08:25:45.919  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:45.919  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 removed from the list
,09-12 08:25:45.921  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:45.921  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:45.921  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.921  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.921  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:45.922  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 08:25:45.922  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:45.922  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:45.922  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:45.924  3993  4042 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 08:25:45.924  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:25:45.925  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:45.925  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:45.925  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:45.925  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.925  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.925  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:45.925  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:45.925  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:45.925  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 08:25:45.925  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.925  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.925  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.925  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.926  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:45.926  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:45.926  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:45.926  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 08:25:45.931  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 08:25:45.932  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 08:25:45.932  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:45.932  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:45.932  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 08:25:45.933  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:45.933  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.933  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.933  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:45.933  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:45.933  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:45.933  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:45.933  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.933  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:45.933  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.933  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.934  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:45.934  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:45.934  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:45.934  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:45.935  3993  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 08:25:45.936  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:45.940  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 08:25:45.941  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:45.941  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 08:25:45.942  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:25:45.942  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 08:25:45.942  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 08:25:45.942  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:45.942  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 08:25:45.943  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:45.946  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:45.949  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 08:25:45.949  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 08:25:45.953  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 08:25:45.954  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 08:25:45.954  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 08:25:45.957  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 08:25:45.959  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 08:25:45.959  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 08:25:45.959  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 08:25:45.960  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 08:25:45.961  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:25:45.963  2759  2880 D BtGatt.GattService: registerClient() - UUID=8f39a8bd-6c1a-430e-bbc5-8b8c91d39612
09-12 08:25:45.964  2759  2798 D BtGatt.GattService: onClientRegistered() - UUID=8f39a8bd-6c1a-430e-bbc5-8b8c91d39612, clientIf=5
09-12 08:25:45.965  3993  4005 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 08:25:45.966  2759  2859 D BtGatt.GattService: start scan with filters
09-12 08:25:45.969  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 08:25:45.969  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 08:25:45.969  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 08:25:45.969  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 08:25:45.969  2759  2816 D BtGatt.ScanManager: handling starting scan
09-12 08:25:45.971  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:25:45.972  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:25:45.972  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 08:25:45.972  2759  2816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:25:45.973  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 08:25:45.975  3993  4042 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 08:25:45.978  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:45.978  3993  4042 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 08:25:45.979  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:45.980  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 08:25:45.980  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.980  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 08:25:45.980  2759  2798 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 08:25:45.980  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 08:25:45.980  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:45.980  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 08:25:45.981  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 08:25:45.981  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 08:25:45.981  2759  2816 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 08:25:45.982  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 08:25:45.982  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 08:25:45.983  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:25:45.983  2759  2770 D BtGatt.GattService: stopScan() - queue size =1
09-12 08:25:45.984  2759  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 08:25:45.984  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 08:25:45.984  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 08:25:45.984  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 08:25:45.984  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 08:25:45.984  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 08:25:45.986  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:45.986  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 08:25:45.986  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 08:25:45.986  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 08:25:45.987  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:25:45.988  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:25:45.988  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:25:45.988  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:45.988  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:45.988  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:45.988  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:25:45.988  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:45.988  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:45.988  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:45.988  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:45.988  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:45.989  3993  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 08:25:45.990  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:45.996  2759  2798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 08:25:45.996  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:45.997  2759  2816 D BtGatt.ScanManager: Starting BLE batch scan
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:45.997  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 08:25:45.997  2759  2816 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 08:25:46.000  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:46.001  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 08:25:46.001  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:25:46.001  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 08:25:46.001  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 08:25:46.001  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:46.001  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 08:25:46.004  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.005  2759  2798 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 08:25:46.005  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.006  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 08:25:46.006  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 08:25:46.007  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.013  2759  2798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 08:25:46.013  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.016  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 08:25:46.018  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 08:25:46.018  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 08:25:46.022  2759  2798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 08:25:46.023  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.023  2759  2816 D BtGatt.ScanManager: stopping BLe Batch
09-12 08:25:46.023  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 08:25:46.023  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 08:25:46.023  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 08:25:46.024  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:25:46.026  2759  2771 D BtGatt.GattService: registerClient() - UUID=64f9e63f-fce7-49e8-bc58-4ee6d2d81a02
09-12 08:25:46.026  2759  2798 D BtGatt.GattService: onClientRegistered() - UUID=64f9e63f-fce7-49e8-bc58-4ee6d2d81a02, clientIf=5
09-12 08:25:46.026  3993  4005 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 08:25:46.027  2759  2770 D BtGatt.GattService: start scan with filters
09-12 08:25:46.028  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 08:25:46.028  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 08:25:46.028  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 08:25:46.028  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 08:25:46.030  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:25:46.030  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:25:46.030  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 08:25:46.031  2759  2798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 08:25:46.031  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.031  2759  2816 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 08:25:46.032  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 08:25:46.035  3993  4042 I io.jxcore.node.ConnectionHelper: start: OK
09-12 08:25:46.037  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.037  3993  4042 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 08:25:46.038  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.038  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 08:25:46.038  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.038  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 08:25:46.038  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 08:25:46.038  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 08:25:46.038  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 08:25:46.038  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 08:25:46.038  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 08:25:46.038  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 08:25:46.039  2759  2798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 08:25:46.039  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:25:46.039  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.040  2759  2771 D BtGatt.GattService: stopScan() - queue size =0
09-12 08:25:46.040  2759  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 08:25:46.040  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 08:25:46.040  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 08:25:46.040  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 08:25:46.040  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 08:25:46.040  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 08:25:46.042  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:46.042  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 08:25:46.042  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 08:25:46.043  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 08:25:46.043  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:25:46.044  2759  2816 D BtGatt.ScanManager: handling starting scan
09-12 08:25:46.046  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:25:46.046  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:25:46.046  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:46.046  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.046  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.046  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:25:46.046  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.046  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.046  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.046  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.047  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.047  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.047  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.047  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.047  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.047  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.047  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.048  3993  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 08:25:46.049  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 08:25:46.057  2759  2798 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 08:25:46.057  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.057  2759  2816 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:46.059  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 08:25:46.061  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:46.061  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 08:25:46.061  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:25:46.061  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 08:25:46.061  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 08:25:46.061  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:46.062  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 08:25:46.065  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.065  2759  2798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 08:25:46.065  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.065  2759  2816 D BtGatt.ScanManager: Starting BLE batch scan
09-12 08:25:46.065  2759  2816 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 08:25:46.066  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 08:25:46.066  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 08:25:46.066  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.074  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 08:25:46.077  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 08:25:46.077  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 08:25:46.079  2759  2798 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 08:25:46.080  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.083  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 08:25:46.083  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 08:25:46.084  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 08:25:46.085  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:25:46.085  2759  2798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 08:25:46.085  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.088  2759  2859 D BtGatt.GattService: registerClient() - UUID=ac7719ce-a788-4a15-a809-771d48ccb0d7
09-12 08:25:46.089  2759  2798 D BtGatt.GattService: onClientRegistered() - UUID=ac7719ce-a788-4a15-a809-771d48ccb0d7, clientIf=5
09-12 08:25:46.089  3993  4004 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 08:25:46.089  2759  2880 D BtGatt.GattService: start scan with filters
,09-12 08:25:46.097  2759  2798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 08:25:46.097  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:25:46.097  2759  2816 D BtGatt.ScanManager: stopping BLe Batch
09-12 08:25:46.099  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 08:25:46.099  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 08:25:46.099  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 08:25:46.099  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 08:25:46.104  2759  2798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 08:25:46.104  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.104  2759  2816 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 08:25:46.109  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 08:25:46.109  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:25:46.110  2759  2798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 08:25:46.110  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:25:46.110  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 08:25:46.112  2759  2816 D BtGatt.ScanManager: handling starting scan
,09-12 08:25:46.114  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 08:25:46.119  3993  4042 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 08:25:46.119  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:25:46.119  3993  4042 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 08:25:46.119  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:25:46.119  2759  2798 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 08:25:46.120  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 08:25:46.120  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:25:46.120  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.120  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 08:25:46.120  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 08:25:46.120  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 08:25:46.120  2759  2816 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 08:25:46.120  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 08:25:46.120  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 08:25:46.121  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 08:25:46.121  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 08:25:46.122  3993  4042 D BluetoothAdapter: STATE_ON
,09-12 08:25:46.123  2759  2859 D BtGatt.GattService: stopScan() - queue size =1
09-12 08:25:46.125  2759  2880 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 08:25:46.125  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 08:25:46.126  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 08:25:46.126  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 08:25:46.126  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 08:25:46.126  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 08:25:46.128  2759  2798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 08:25:46.128  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.128  2759  2816 D BtGatt.ScanManager: Starting BLE batch scan
09-12 08:25:46.128  2759  2816 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 08:25:46.129  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:46.129  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 08:25:46.129  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 08:25:46.130  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 08:25:46.130  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 08:25:46.133  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 08:25:46.133  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 08:25:46.133  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:46.133  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:25:46.133  3993  4042 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 08:25:46.134  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.134  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.134  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:25:46.134  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.134  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:25:46.134  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.135  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.135  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.135  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.135  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.136  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.136  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.138  2759  2798 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 08:25:46.138  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:25:46.138  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.138  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.138  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.139  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.140  3993  4042 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 08:25:46.141  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.141  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:25:46.142  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.142  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.142  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.142  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.143  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
,09-12 08:25:46.143  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.143  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.143  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.143  2759  2798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 08:25:46.143  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.143  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.143  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.143  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.144  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.147  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.147  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.148  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.148  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.150  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 08:25:46.150  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.150  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.151  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.151  2759  2798 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 08:25:46.151  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.152  2759  2816 D BtGatt.ScanManager: stopping BLe Batch
09-12 08:25:46.151  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:25:46.152  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.153  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.153  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.153  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.153  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.153  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.153  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.153  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.153  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.153  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.154  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 08:25:46.154  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.154  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.154  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.155  3993  4042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 08:25:46.155  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.155  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.155  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.156  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.156  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.156  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.156  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.156  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.156  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.156  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.156  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.156  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.156  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.156  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.157  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.157  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.157  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.157  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.158  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 08:25:46.158  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.158  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.158  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 08:25:46.158  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.158  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.158  2759  2798 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 08:25:46.158  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:25:46.158  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.159  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.159  2759  2816 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 08:25:46.159  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.159  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.159  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.159  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.159  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.159  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.159  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.160  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 08:25:46.160  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 08:25:46.160  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.160  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.161  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 08:25:46.163  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 08:25:46.163  2759  2798 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 08:25:46.163  2759  2798 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:25:46.163  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 08:25:46.163  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 08:25:46.163  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 08:25:46.164  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 08:25:46.164  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:25:46.164  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:25:46.164  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.164  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:25:46.164  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.164  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.165  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
,09-12 08:25:46.165  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.165  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.165  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.165  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.165  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.165  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.165  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.166  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.166  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 08:25:46.166  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.166  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.167  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 08:25:46.167  3993  4042 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 08:25:46.167  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 08:25:46.171  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 08:25:46.172  3993  4042 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 08:25:46.172  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-12 08:25:46.173  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 08:25:46.173  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 08:25:46.173  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 08:25:46.173  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 08:25:46.173  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 08:25:46.173  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-12 08:25:46.174  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 08:25:46.174  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 08:25:46.174  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 08:25:46.174  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 08:25:46.174  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 08:25:46.175  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 08:25:46.175  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-12 08:25:46.176  3993  4042 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 08:25:46.176  3993  4042 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 08:25:46.176  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 08:25:46.176  3993  4042 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...,
09-12 08:25:46.176  3993  4042 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 08:25:46.176  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 08:25:46.176  3993  4042 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...,
09-12 08:25:46.176  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 08:25:46.180  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 08:25:46.180  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-12 08:25:46.180  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 08:25:46.181  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 08:25:46.181  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-12 08:25:46.181  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 08:25:46.181  3993  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 08:25:46.182  3993  4042 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-12 08:25:46.182  3993  4054 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 437)
09-12 08:25:46.182  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.183  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:25:46.183  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.183  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:25:46.183  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.183  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.183  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-12 08:25:46.183  3993  4054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 08:25:46.184  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.184  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.184  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.184  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.184  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.184  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.184  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.184  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.184  3993  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 437
09-12 08:25:46.184  3993  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 437)
09-12 08:25:46.185  3993  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 437),
09-12 08:25:46.185  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.185  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 08:25:46.185  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.185  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.186  3993  4042 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-12 08:25:46.187  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.187  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.187  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.187  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.187  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.187  3993  4054 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 437)
,09-12 08:25:46.187  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.187  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.187  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.187  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.187  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.187  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.187  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 08:25:46.187  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.188  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.189  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.189  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.189  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.189  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list,
09-12 08:25:46.189  3993  4042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 08:25:46.190  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.190  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.190  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.190  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:25:46.190  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.190  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.190  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.190  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.190  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.191  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.191  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.191  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.191  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.191  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.192  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.192  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.192  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.192  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.193  3993  4042 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 08:25:46.193  3993  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 08:25:46.193  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 08:25:46.193  3993  4042 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 08:25:46.193  3993  4042 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 08:25:46.193  3993  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-12 08:25:46.193  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 08:25:46.194  3993  4042 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 08:25:46.194  3993  4042 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 08:25:46.194  3993  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 08:25:46.194  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 08:25:46.194  3993  4042 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 08:25:46.194  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:25:46.194  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.194  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.194  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.194  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.194  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.195  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.195  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.195  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.195  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.195  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.195  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.195  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.195  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.196  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.196  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.196  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.196  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.197  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.197  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.197  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.197  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.197  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.197  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.197  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.197  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.197  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.197  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.197  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.197  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.197  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.197  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.197  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.198  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.198  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:25:46.198  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.198  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.198  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.198  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.198  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.198  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.198  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.198  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.198  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.198  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.198  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.199  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.200  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.200  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 08:25:46.200  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.200  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.201  3993  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 08:25:46.201  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:46.202  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 08:25:46.202  3993  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-12 08:25:46.202  3993  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 08:25:46.203  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 08:25:46.203  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 08:25:46.203  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 08:25:46.203  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.203  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 08:25:46.203  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 08:25:46.203  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 08:25:46.203  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.203  3993  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 08:25:46.204  3993  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 08:25:46.204  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.204  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.204  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 08:25:46.204  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 08:25:46.204  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 08:25:46.204  3993  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 08:25:46.204  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.204  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.205  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:46.205  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:25:46.205  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:25:46.205  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:25:46.206  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.206  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.206  3993  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 08:25:46.206  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.206  3993  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 08:25:46.206  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.206  3993  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
09-12 08:25:46.206  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.206  3993  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 08:25:46.206  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.206  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.206  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.206  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.206  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.207  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.207  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.207  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.207  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.207  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:25:46.208  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.208  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 08:25:46.208  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.208  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.209  3993  4042 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 08:25:46.209  3993  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 08:25:46.209  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 08:25:46.209  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 08:25:46.210  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.210  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.210  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.210  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.210  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.210  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.210  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.210  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.210  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.210  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.210  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.210  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.210  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.210  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.212  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 08:25:46.212  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.212  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.212  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.215  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.215  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.215  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 08:25:46.215  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:25:46.215  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.215  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.215  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
09-12 08:25:46.215  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.216  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
,09-12 08:25:46.216  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.216  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.216  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.216  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.216  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.216  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:25:46.216  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.216  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:25:46.216  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.217  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:25:46.217  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:25:46.217  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:25:46.217  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:25:46.217  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.217  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.217  3993  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9bc not in the list
,09-12 08:25:46.218  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.218  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.218  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:25:46.218  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:25:46.218  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.218  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:25:46.218  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:25:46.219  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 08:25:46.219  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:25:46.219  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:25:46.219  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc2d45 not in the list
09-12 08:25:46.219  3993  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-12 08:25:46.219  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 08:25:46.220  3993  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 08:25:46.220  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 08:25:46.220  3993  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-12 08:25:46.220  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 08:25:46.221  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 08:25:46.221  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 08:25:46.221  3993  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 08:25:46.222  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 08:25:46.222  3993  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 08:25:46.222  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 08:25:46.222  3993  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-12 08:25:46.222  3993  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 08:25:46.222  3993  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 08:25:46.222  3993  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 08:25:46.223  3993  4042 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 08:25:46.223  3993  4042 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 08:25:46.223  3993  4042 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-12 08:25:46.223  3993  4042 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 08:25:46.223  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:25:46.223  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22bd49f added. We now have 2 listener(s)
,09-12 08:25:46.224  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:25:46.225  3993  4042 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 08:25:46.225   872  2228 D WifiService: setWifiEnabled: true pid=3993, uid=10000
09-12 08:25:46.225   872  2228 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 08:25:46.226  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:25:46.226  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96c29ec added. We now have 3 listener(s)
,09-12 08:25:46.226  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:25:46.233  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:25:46.233  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5bf1b5 added. We now have 4 listener(s)
09-12 08:25:46.233  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:25:46.235  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:25:46.235  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c9404a added. We now have 5 listener(s)
09-12 08:25:46.235  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:25:46.239   872   882 D WifiService: setWifiEnabled: false pid=3993, uid=10000
,09-12 08:25:46.239   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 08:25:46.242  2759  2794 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 08:25:46.242  2759  2794 D BluetoothAdapterProperties: Setting state to 13
,09-12 08:25:46.242  2759  2794 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 08:25:46.243  2759  2794 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 08:25:46.244  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:25:46.244  2759  2794 I BluetoothAdapterState: Entering PendingCommandState
09-12 08:25:46.244  2759  2798 D BluetoothAdapterProperties: Scan Mode:20
09-12 08:25:46.244  2759  2794 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 08:25:46.246  2759  2759 D HeadsetService: Received stop request...Stopping profile...
09-12 08:25:46.251  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:46.251  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:25:46.252  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:46.252  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:46.252  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 08:25:46.254  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:46.257  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:46.257  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 08:25:46.259   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 08:25:46.259   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 08:25:46.259   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 08:25:46.259   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 08:25:46.260  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:46.260  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:25:46.260  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:46.260  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:25:46.261   872   885 I ActivityManager: Start proc 4059:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-12 08:25:46.263  1953  1963 D BluetoothHeadset: Proxy object disconnected
,09-12 08:25:46.264  2759  2759 D BluetoothMapService: onReceive
,09-12 08:25:46.264  2759  2759 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 08:25:46.264  2759  2759 D BluetoothMapService: STATE_TURNING_OFF
,09-12 08:25:46.264   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 08:25:46.264  2759  2759 D A2dpService: Received stop request...Stopping profile...
,09-12 08:25:46.265  2759  2872 D A2dpStateMachine: Exit Disconnected: -1
09-12 08:25:46.264   872   872 D BluetoothHeadset: Proxy object disconnected
,09-12 08:25:46.265   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 08:25:46.265  1362  1374 D BluetoothHeadset: Proxy object disconnected
,09-12 08:25:46.265  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.267   872   872 D BluetoothA2dp: Proxy object disconnected
,09-12 08:25:46.267  2759  2759 V BluetoothAdapterState: isTurningOff()=true
,09-12 08:25:46.268  2759  2759 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:46.268  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.268  2759  2759 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:46.269  2759  2759 D HidService: Received stop request...Stopping profile...
,09-12 08:25:46.269  2759  2759 D HidService: Stopping Bluetooth HidService
,09-12 08:25:46.269  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-12 08:25:46.269  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:46.270  1362  1362 D BluetoothA2dp: Proxy object disconnected
09-12 08:25:46.270  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,09-12 08:25:46.271  2759  2759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 08:25:46.271  2759  2848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 08:25:46.271  2759  2848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:46.271  2759  2848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:46.272   872  1895 D DhcpClient: Clearing IP address
09-12 08:25:46.272  2759  2798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 08:25:46.274  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.270  1362  1362 D HidProfile: Bluetooth service disconnected
,09-12 08:25:46.274  2759  2798 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 08:25:46.274   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-12 08:25:46.276  2759  2759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 08:25:46.277  2759  2759 D BluetoothMapService: MAP Service closeService in
09-12 08:25:46.277  2759  2759 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 08:25:46.277  2759  2759 D ObexServerSockets0: shutdown(block = true)
,09-12 08:25:46.277  2759  2881 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 08:25:46.278   371   870 D CommandListener: Setting iface cfg
09-12 08:25:46.280  1520  2488 V NativeCrypto: Read error: ssl=0x9a79e000: I/O error during system call, Connection timed out
09-12 08:25:46.281  1520  2488 V NativeCrypto: SSL shutdown failed: ssl=0x9a79e000: I/O error during system call, Broken pipe
09-12 08:25:46.283   872  2225 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-12 08:25:46.284   872  1891 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-12 08:25:46.287  2759  2759 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 08:25:46.287  2759  2882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 08:25:46.287  2759  2856 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 08:25:46.287  2759  2759 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 08:25:46.287  2759  2759 I BtOppRfcommListener: stopping Accept Thread
09-12 08:25:46.288  2759  3590 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 08:25:46.288  2759  3590 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 08:25:46.288   872  1896 D DhcpClient: Receive thread stopped
09-12 08:25:46.290  2759  2759 D HealthService: Received stop request...Stopping profile...
09-12 08:25:46.291  2759  2759 D PanService: Received stop request...Stopping profile...
09-12 08:25:46.291   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 08:25:46.292   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 08:25:46.294   394   394 E Parcel  : Reading a NULL string not supported here.
,09-12 08:25:46.295   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 08:25:46.296   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 08:25:46.293  2759  2759 D BluetoothMapService: Received stop request...Stopping profile...
09-12 08:25:46.297  2759  2759 D BluetoothMapService: stop()
09-12 08:25:46.297  2759  2759 D BluetoothMapAppObserver: deinitObservers()
09-12 08:25:46.297  2759  2759 D BluetoothMapAppObserver: removeReceiver()
,09-12 08:25:46.298   371   870 D CommandListener: Clearing all IP addresses on wlan0
09-12 08:25:46.299  2759  2759 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:46.299  2759  2759 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:46.299  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.299  2759  2759 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:46.300   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-12 08:25:46.300  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 08:25:46.300  1362  1362 D PanProfile: Bluetooth service disconnected
09-12 08:25:46.300  2759  2848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:46.300  2759  2848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:46.300  1362  1362 D BluetoothMap: Proxy object disconnected
09-12 08:25:46.300  2759  2759 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:46.300  1362  1362 D MapProfile: Bluetooth service disconnected
09-12 08:25:46.300  2759  2759 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:46.300  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.300  2759  2759 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:46.300  2759  2759 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 08:25:46.300  2759  2759 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 08:25:46.301  2759  2848 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 08:25:46.301  2759  2848 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 08:25:46.301  2759  2848 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 08:25:46.301  2759  2848 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 08:25:46.301  2759  2759 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:46.301  2759  2798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 08:25:46.301  2759  2759 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:46.301  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.301  2759  2759 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:46.301  2759  2798 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 08:25:46.301  2759  2759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 08:25:46.301  2759  2798 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 08:25:46.302  2759  2759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 08:25:46.302  2759  2759 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:46.302  2759  2759 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:46.302  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.302  2759  2759 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:46.302  2759  2759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 08:25:46.302  2759  2759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 08:25:46.305  2759  2759 D BluetoothMapService: MAP Service closeService in
,09-12 08:25:46.305  2759  2759 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:46.305  2759  2759 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:46.305  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.305  2759  2759 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:46.306  2759  2794 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 08:25:46.306  2759  2794 D BluetoothAdapterProperties: Setting state to 15
09-12 08:25:46.306  2759  2794 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 08:25:46.306  2759  2794 I BluetoothAdapterState: Entering BleOnState
09-12 08:25:46.306   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 08:25:46.306   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:46.307  1362  2059 D BluetoothMap: onBluetoothStateChange: up=false
09-12 08:25:46.307  2759  2759 D BluetoothMapService: cleanup()
09-12 08:25:46.307  2759  2759 D BluetoothMapService: MAP Service closeService in
09-12 08:25:46.307  1362  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 08:25:46.307   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 08:25:46.308  1362  1374 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 08:25:46.308   872  1891 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-12 08:25:46.308  1953  1967 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 08:25:46.308   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:46.309  1362  2059 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 08:25:46.309  1362  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:46.310  1362  1374 D BluetoothPan: onBluetoothStateChange on: false
09-12 08:25:46.310  2759  2794 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 08:25:46.310  2759  2794 D BluetoothAdapterProperties: Setting state to 16
09-12 08:25:46.310  2759  2794 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 08:25:46.311  2759  2794 D BluetoothAdapterProperties: onBleDisable
,09-12 08:25:46.311  2759  2794 I BluetoothAdapterState: Entering PendingCommandState
09-12 08:25:46.311  2759  2795 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 08:25:46.311  2759  2798 D BluetoothAdapterProperties: Scan Mode:20
09-12 08:25:46.312  2759  2848 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 08:25:46.312  2759  2848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:46.313  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:46.313  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:46.316  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:46.316  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 08:25:46.318  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:46.318  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:46.318  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:46.318  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 08:25:46.320   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 08:25:46.320  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:46.320  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:46.321  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:46.321  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:25:46.322  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.323  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.324  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.325   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 08:25:46.330  1912  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 08:25:46.342   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:25:46.367   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:25:46.368   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 08:25:46.368   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:25:46.369   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 08:25:46.373  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.374  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:46.378  3582  3582 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@30155ec and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 08:25:46.383  4059  4059 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 08:25:46.401  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 08:25:46.407  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 08:25:46.408   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d22c795:true
,09-12 08:25:46.413   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-12 08:25:46.414   872  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 08:25:46.414   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 08:25:46.419   872   883 I ActivityManager: Start proc 4080:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 08:25:46.427  4059  4059 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 08:25:46.428  4059  4059 D BluetoothMap: Create BluetoothMap proxy object
,09-12 08:25:46.434  4059  4059 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 08:25:46.440  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-12 08:25:46.451  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 08:25:46.453   872  2225 I ActivityManager: Killing 3582:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 08:25:46.514  2759  2798 I bt_hci  : shut_down
,09-12 08:25:46.515  2759  2817 D bt_hwcfg: hw_epilog_process
,09-12 08:25:46.516  2759  2817 I bt_vendor: low_power_mode_cb
,09-12 08:25:46.542  2759  2817 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-12 08:25:46.542  2759  2817 I bt_vendor: epilog_cb
09-12 08:25:46.542  2759  2817 I bt_hci  : epilog_finished_callback
,09-12 08:25:46.550  2759  2798 I bt_hci_h4: hal_close
,09-12 08:25:46.550  2759  2798 I bt_userial_vendor: device fd = 51 close
,09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.620  4080  4080 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:25:46.620  4080  4080 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:25:46.626  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 08:25:46.632  4059  4059 D DockEventReceiver: finishStartingService: stopping service
09-12 08:25:46.636  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 08:25:46.639   872  1701 I ActivityManager: Killing 3743:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 08:25:46.706  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 08:25:46.750   872  1701 I ActivityManager: Start proc 4111:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 08:25:46.756  2759  2795 D bt_stack_manager: event_shut_down_stack finished.
,09-12 08:25:46.757  2759  2794 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 08:25:46.758  2759  2794 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 08:25:46.758  2759  2759 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 08:25:46.758  2759  2759 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 08:25:46.758  2759  2759 D BtGatt.GattService: stop()
09-12 08:25:46.758  2759  2759 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 08:25:46.760  2759  2759 V BluetoothAdapterState: isTurningOff()=false
09-12 08:25:46.760  2759  2759 V BluetoothAdapterState: isTurningOn()=false
,09-12 08:25:46.760  2759  2759 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:46.761  2759  2759 V BluetoothAdapterState: isBleTurningOff()=true
09-12 08:25:46.761  2759  2794 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 08:25:46.761  2759  2794 D BluetoothAdapterProperties: Setting state to 10
09-12 08:25:46.761  2759  2794 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 08:25:46.761  2759  2794 I BluetoothAdapterState: Entering OffState
09-12 08:25:46.763   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 08:25:46.772  2759  2759 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 08:25:46.772  2759  2759 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 08:25:46.773  2759  2759 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 08:25:46.774  2759  2795 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 08:25:46.776  2759  2795 D bt_stack_manager: event_clean_up_stack finished.
,09-12 08:25:46.778  2759  2759 I art     : System.exit called, status: 0
,09-12 08:25:46.778  2759  2759 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 08:25:46.798  4111  4111 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 08:25:46.822   872  2226 I ActivityManager: Process com.android.bluetooth (pid 2759) has died
,09-12 08:25:46.841  4111  4111 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 08:25:46.903  4080  4098 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 08:25:46.908  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 08:25:46.911  1725  1725 D SystemUpdateService: onCreate
,09-12 08:25:46.913  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 08:25:46.927  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 08:25:46.927  1725  4138 I SystemUpdateService: active receiver: enabled
,09-12 08:25:46.932   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6be7ed6:true
,09-12 08:25:46.935  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-12 08:25:46.936  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 08:25:46.939  1725  4138 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 08:25:46.940  1725  2466 I iu.UploadsManager: num queued entries: 0
,09-12 08:25:46.941  1725  2466 I iu.UploadsManager: num updated entries: 0
09-12 08:25:46.941  1725  2466 I iu.SyncManager: NEXT; no task
,09-12 08:25:46.942  1725  4138 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 08:25:46.946  1725  4138 I SystemUpdateService: now status is 0 (complete)
09-12 08:25:46.946  1725  4138 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 08:25:46.946  1725  4138 I SystemUpdateService: file has been verified
,09-12 08:25:46.947  1725  4138 I SystemUpdateService: OTA package size = 12249756
09-12 08:25:46.952  1725  4138 I SystemUpdateService: showing system update notification
09-12 08:25:46.952   872  2227 I ActivityManager: Start proc 4140:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 08:25:46.967  1912  1921 I art     : Background partial concurrent mark sweep GC freed 13532(984KB) AllocSpace objects, 16(320KB) LOS objects, 40% free, 22MB/36MB, paused 5.184ms total 55.854ms
,09-12 08:25:46.981  1725  1725 D SystemUpdateService: onDestroy
,09-12 08:25:47.004  4140  4140 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 08:25:47.008  4140  4140 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:25:47.018  4140  4140 D SprintDMHelper: simOperator: 
09-12 08:25:47.018  4140  4140 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 08:25:47.036   872   883 I ActivityManager: Start proc 4152:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 08:25:47.037   872   883 I ActivityManager: Killing 2965:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 08:25:47.189   872  2005 I ActivityManager: Start proc 4167:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 08:25:47.193  2861  4166 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 08:25:47.204   872  1969 I ActivityManager: Killing 3668:android.process.acore/u0a5 (adj 15): empty #17
,09-12 08:25:47.281  4167  4167 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 08:25:47.343  4167  4167 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 08:25:47.343  4167  4167 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 08:25:47.343  4167  4167 I GAv4    :   adb logcat -s GAv4
,09-12 08:25:47.366  4167  4167 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 08:25:47.374  4167  4167 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 08:25:47.396  4167  4185 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 08:25:47.498  4167  4167 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 08:25:47.530  4167  4167 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 08:25:47.538  4167  4167 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4238-4242)
,09-12 08:25:47.538  4167  4167 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 08:25:47.554  4167  4167 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8fc121c}
,09-12 08:25:47.555  4167  4167 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 08:25:47.555  4167  4167 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 08:25:47.561  4167  4167 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 08:25:47.563  4167  4167 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 08:25:47.585  4167  4167 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 08:25:47.595  4167  4167 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 08:25:47.596  4167  4167 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 08:25:47.596  4167  4167 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 08:25:47.596  4167  4167 I Adreno  : Build Date                       : 10/20/15
09-12 08:25:47.596  4167  4167 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 08:25:47.596  4167  4167 I Adreno  : Local Branch                     : M14
09-12 08:25:47.596  4167  4167 I Adreno  : Remote Branch                    : 
09-12 08:25:47.596  4167  4167 I Adreno  : Remote Branch                    : 
09-12 08:25:47.596  4167  4167 I Adreno  : Reconstruct Branch               : 
,09-12 08:25:47.646  4167  4213 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 08:25:47.661  4167  4167 I NSApplication: Starting up...
,09-12 08:25:47.696   872  2227 I ActivityManager: Start proc 4218:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 08:25:47.697   872  2227 I ActivityManager: Killing 3822:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 08:25:47.779  4218  4218 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 08:25:47.957   872   883 I ActivityManager: Killing 3837:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 08:25:49.255   872   883 D WifiService: setWifiEnabled: true pid=3993, uid=10000
,09-12 08:25:49.255   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 08:25:49.270   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-12 08:25:49.280  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:49.281  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:49.281  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:49.281  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 08:25:49.284  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:49.285  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:25:49.285  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:49.285  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:25:49.302   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-12 08:25:49.303   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 08:25:49.305   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 08:25:49.306   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 08:25:49.306   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 08:25:49.307   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 08:25:49.307   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 08:25:49.320   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 08:25:49.321   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.50 rxSuccessRate=11.38 delta 1000 -> 994
09-12 08:25:49.321   371   870 D CommandListener: Setting iface cfg
09-12 08:25:49.322   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 08:25:49.322   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 08:25:49.330   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 08:25:49.330   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 08:25:49.330   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 08:25:49.330   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 08:25:49.336   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 08:25:49.406   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 08:25:49.408  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 08:25:49.824  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 08:25:49.866  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 08:25:49.867  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 08:25:49.872   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:25:49.884   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 08:25:49.884   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 08:25:49.884   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 08:25:49.911   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 08:25:49.924   371   870 D CommandListener: Setting iface cfg
,09-12 08:25:49.925   872  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 08:25:49.940   872  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-12 08:25:49.942   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 08:25:49.954   872  4242 D DhcpClient: Receive thread started
,09-12 08:25:50.035   872  1307 E native  : do suspend false
,09-12 08:25:50.054   872  1895 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 08:25:50.070   872  4242 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,09-12 08:25:50.071   872  1895 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,09-12 08:25:50.075   872  1895 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 08:25:50.088   872  4242 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 08:25:50.089   872  1895 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 08:25:50.094   371   870 D CommandListener: Setting iface cfg
,09-12 08:25:50.106   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 08:25:50.106   872  1895 D DhcpClient: Scheduling renewal in 86399s
,09-12 08:25:50.131   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 08:25:50.134   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 08:25:50.135   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 08:25:50.136   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 08:25:50.144   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 08:25:50.149   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 08:25:50.195   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 08:25:50.195   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 08:25:50.198   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-12 08:25:50.199   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-12 08:25:50.200   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 08:25:50.205   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 08:25:50.210   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 08:25:50.210   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 08:25:50.210   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-12 08:25:50.210   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 08:25:50.210   872  1309 D ConnectivityService:    accepting network in place of null
09-12 08:25:50.211   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 08:25:50.212   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 08:25:50.225   872  4241 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136929, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 08:25:50.247   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:25:50.290   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:25:50.295   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 08:25:50.295   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:25:50.296   872  4240 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 08:25:50.300   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 08:25:50.301   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 08:25:50.325  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:50.325  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 08:25:50.325  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:50.326  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:25:50.329  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:25:50.329  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 08:25:50.329  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 08:25:50.329  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:50.329  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:25:50.334  1725  1725 D SystemUpdateService: onCreate
,09-12 08:25:50.337  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 08:25:50.340  1725  4253 I SystemUpdateService: active receiver: enabled
,09-12 08:25:50.344  1725  4253 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 08:25:50.349  1725  4253 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 08:25:50.349  1725  4253 I SystemUpdateService: now status is 0 (complete)
09-12 08:25:50.349  1725  4253 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 08:25:50.349  1725  4253 I SystemUpdateService: file has been verified
09-12 08:25:50.349  1725  4253 I SystemUpdateService: OTA package size = 12249756
,09-12 08:25:50.354  1725  4253 I SystemUpdateService: showing system update notification
,09-12 08:25:50.359  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 08:25:50.361  1725  2466 I iu.UploadsManager: num queued entries: 0
09-12 08:25:50.361  1725  2466 I iu.UploadsManager: num updated entries: 0
,09-12 08:25:50.362  1725  2466 I iu.SyncManager: NEXT; no task
09-12 08:25:50.363  1725  4257 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 08:25:50.364  1725  4257 W BaseAppContext: Using Auth Proxy for data requests.
09-12 08:25:50.364  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 08:25:50.365  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 08:25:50.365  1725  4257 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 08:25:50.367  4140  4140 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:25:50.371  1725  1725 D SystemUpdateService: onDestroy
,09-12 08:25:50.372  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 08:25:50.374  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:25:50.379  4140  4140 D SprintDMHelper: simOperator: 
,09-12 08:25:50.379  4140  4140 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 08:25:50.394   872  4240 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 06:25:50 GMT], X-Android-Received-Millis=[1473661550393], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473661550367]}
,09-12 08:25:50.401   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 08:25:50.402   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-12 08:25:50.402   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 08:25:50.404   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 08:25:50.404  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-12 08:25:50.404  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 08:25:50.404  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:25:50.405  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:25:50.427  1725  4257 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-12 08:25:50.520  2861  4259 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 08:25:50.575  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:25:50.575  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 08:25:50.575  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:25:50.575  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:25:50.597  3724  4263 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 08:25:50.597  3724  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at blb.a(PG:3937)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at czp.a(PG:18188)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:25:50.597  3724  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	... 12 more
09-12 08:25:50.597  3724  4263 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at fal.a(PG:38)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:25:50.597  3724  4263 E HttpOperation: 	... 14 more
,09-12 08:25:50.674  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 08:25:50.674  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:25:50.674  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:25:50.674  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:25:50.695  3724  4263 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 08:25:50.695  3724  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at hec.a(PG:42)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at hee.a(PG:102)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at czr.a(PG:65)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at kka.a(PG:108)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at czp.a(PG:19176)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:25:50.695  3724  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	... 15 more
09-12 08:25:50.695  3724  4263 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at fal.a(PG:38)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:25:50.695  3724  4263 E HttpOperation: 	... 17 more
09-12 08:25:50.696  3724  4263 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 08:25:50.696  3724  4263 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at hec.a(PG:42)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at hee.a(PG:102)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at czr.a(PG:65)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at kka.a(PG:108)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	... 15 more
09-12 08:25:50.696  3724  4263 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at fal.a(PG:38)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 08:25:50.696  3724  4263 E ExperimentLoader: 	... 17 more
,09-12 08:25:50.843   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 133407, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:25:51.296   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 08:25:52.047   872  2226 I ActivityManager: Killing 2168:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 08:25:52.263   872  1372 D WifiService: setWifiEnabled: false pid=3993, uid=10000
09-12 08:25:52.263   872  1372 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 08:25:52.299  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 08:25:52.308   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 08:25:52.308   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 08:25:52.309   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 08:25:52.309   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 08:25:52.333   872  1895 D DhcpClient: Clearing IP address
,09-12 08:25:52.334   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-12 08:25:52.340  1520  4266 V NativeCrypto: Read error: ssl=0x9a37b600: I/O error during system call, Connection timed out
,09-12 08:25:52.341   371   870 D CommandListener: Setting iface cfg
,09-12 08:25:52.343   872  4242 D DhcpClient: Receive thread stopped
,09-12 08:25:52.367   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 08:25:52.367   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 08:25:52.372  1520  4266 V NativeCrypto: SSL shutdown failed: ssl=0x9a37b600: I/O error during system call, Broken pipe
,09-12 08:25:52.374   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 08:25:52.375   394   394 E Parcel  : Reading a NULL string not supported here.
09-12 08:25:52.375   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-12 08:25:52.377   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 08:25:52.413   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:25:52.440   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:25:52.440   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 08:25:52.440   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 08:25:52.440   371   870 D CommandListener: Clearing all IP addresses on wlan0
,09-12 08:25:52.441   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-12 08:25:52.444  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:52.444  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:52.444  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:52.444  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 08:25:52.445  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:52.445  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:52.445  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:52.445  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:25:52.454  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 08:25:52.458  1725  1725 D SystemUpdateService: onCreate
,09-12 08:25:52.463  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 08:25:52.470  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 08:25:52.472  1725  2466 I iu.UploadsManager: num queued entries: 0
09-12 08:25:52.472  1725  2466 I iu.UploadsManager: num updated entries: 0
,09-12 08:25:52.478  1725  4277 I SystemUpdateService: active receiver: enabled
,09-12 08:25:52.480  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 08:25:52.481  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 08:25:52.483  4140  4140 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:25:52.497  4140  4140 D SprintDMHelper: simOperator: 
,09-12 08:25:52.497  4140  4140 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 08:25:52.501  1725  2466 I iu.SyncManager: NEXT; no task
,09-12 08:25:52.506  1725  4277 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 08:25:52.515  2861  4281 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 08:25:52.521  1725  4277 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 08:25:52.522  1725  4277 I SystemUpdateService: now status is 0 (complete)
09-12 08:25:52.522  1725  4277 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 08:25:52.522  1725  4277 I SystemUpdateService: file has been verified
09-12 08:25:52.525  1725  4277 I SystemUpdateService: OTA package size = 12249756
,09-12 08:25:52.533   371   870 E Netd    : netlink response contains error (No such file or directory)
,09-12 08:25:52.536   872  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 08:25:52.541   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:25:52.544  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:52.544  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 08:25:52.544  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:52.544  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:25:52.545  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:52.545  1912  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:52.545  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:25:52.545  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:52.545  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:25:52.552   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 08:25:52.555  1725  4277 I SystemUpdateService: showing system update notification
,09-12 08:25:52.571  1725  1725 D SystemUpdateService: onDestroy
,09-12 08:25:52.625  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:25:52.649  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 08:25:52.649  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 08:25:52.649  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:25:52.649  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:25:52.681  3686  3686 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 08:25:52.681  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 08:25:52.681  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 08:25:55.319   872   889 I ActivityManager: Start proc 4285:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 08:25:55.464  4285  4285 D AdapterServiceConfig: Adding HeadsetService
,09-12 08:25:55.465  4285  4285 D AdapterServiceConfig: Adding A2dpService
,09-12 08:25:55.465  4285  4285 D AdapterServiceConfig: Adding HidService
,09-12 08:25:55.465  4285  4285 D AdapterServiceConfig: Adding HealthService
,09-12 08:25:55.465  4285  4285 D AdapterServiceConfig: Adding PanService
,09-12 08:25:55.465  4285  4285 D AdapterServiceConfig: Adding GattService
09-12 08:25:55.466  4285  4285 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 08:25:55.490   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@539f98a:true
,09-12 08:25:55.491  4285  4285 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 08:25:55.503  4285  4285 I bt_bluedroid: init
,09-12 08:25:55.505  4285  4297 I BluetoothAdapterState: Entering OffState
,09-12 08:25:55.507  4285  4298 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 08:25:55.507  4285  4298 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 08:25:55.507  4285  4298 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 08:25:55.507  4285  4298 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 08:25:55.508  4285  4285 I bt_bluedroid: get_profile_interface socket
,09-12 08:25:55.510  4285  4301 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 08:25:55.511  4285  4301 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 08:25:55.512  4285  4285 I bt_bluedroid: get_profile_interface sdp
,09-12 08:25:55.516  4285  4296 I bt_bluedroid: config_hci_snoop_log
,09-12 08:25:55.517   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 08:25:55.524  4285  4297 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 08:25:55.524  4285  4297 D BluetoothAdapterProperties: Setting state to 14
09-12 08:25:55.525  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 08:25:55.529  4285  4297 D BluetoothBondStateMachine: make
09-12 08:25:55.532  4285  4302 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 08:25:55.539  4285  4297 I BluetoothAdapterState: Entering PendingCommandState
,09-12 08:25:55.541  4285  4285 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 08:25:55.549  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:25:55.551  4285  4285 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 08:25:55.552  4285  4285 D BtGatt.GattService: Received start request. Starting profile...
09-12 08:25:55.553  4285  4285 D BtGatt.GattService: start()
09-12 08:25:55.553  4285  4285 I bt_bluedroid: get_profile_interface gatt
,09-12 08:25:55.555  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:25:55.555  4285  4285 D BtGatt.AdvertiseManager: advertise manager created
,09-12 08:25:55.567  4285  4285 V BluetoothAdapterState: isTurningOff()=false
09-12 08:25:55.567  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:55.567  4285  4285 V BluetoothAdapterState: isBleTurningOn()=true
09-12 08:25:55.567  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:55.567  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 08:25:55.568  4285  4297 I bt_bluedroid: enable
09-12 08:25:55.568  4285  4298 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 08:25:55.569  4285  4298 I bt_hci  : start_up
,09-12 08:25:55.580  4285  4298 I bt_vendor: alloc value 0xb3a61189
09-12 08:25:55.580  4285  4298 I bt_vendor: init
09-12 08:25:55.580  4285  4298 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 08:25:55.580  4285  4298 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 08:25:55.688  4285  4298 D bt_hci  : start_up starting async portion
,09-12 08:25:55.688  4285  4305 I bt_hci  : event_finish_startup
09-12 08:25:55.688  4285  4305 I bt_hci_h4: hal_open
09-12 08:25:55.689  4285  4305 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 08:25:55.698  4285  4305 I bt_userial_vendor: device fd = 51 open
,09-12 08:25:55.730  4285  4305 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,09-12 08:25:55.762  4285  4305 D bt_hwcfg: Chipset BCM4354A2
,09-12 08:25:55.762  4285  4305 D bt_hwcfg: Target name = [BCM4354A2]
09-12 08:25:55.762  4285  4305 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 08:25:56.457  4285  4305 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 08:25:56.458  4285  4305 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 08:25:56.458  4285  4305 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 08:25:56.575  4285  4305 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 08:25:56.576  4285  4305 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 08:25:56.606  4285  4305 I bt_hwcfg: vendor lib fwcfg completed
,09-12 08:25:56.607  4285  4305 I bt_vendor: firmware callback
,09-12 08:25:56.607  4285  4305 I bt_hci  : firmware_config_callback
,09-12 08:25:56.619  4285  4307 I bt_btu  : btu_task pending for preload complete event
,09-12 08:25:56.619  4285  4307 I bt_btu_task: Bluetooth chip preload is complete
,09-12 08:25:56.619  4285  4307 I bt_btu  : btu_task received preload complete event
,09-12 08:25:56.630  4285  4307 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 08:25:56.631  4285  4307 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 08:25:56.631  4285  4307 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 08:25:56.631  4285  4307 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 08:25:56.631  4285  4307 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 08:25:56.632  4285  4307 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 08:25:56.632  4285  4307 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 08:25:56.632  4285  4307 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 08:25:56.633  4285  4307 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 08:25:56.633  4285  4307 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 08:25:56.633  4285  4307 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 08:25:56.633  4285  4307 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 08:25:56.634  4285  4307 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 08:25:56.634  4285  4307 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 08:25:56.634  4285  4307 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 08:25:56.765  4285  4307 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ded9d
09-12 08:25:56.766  4285  4307 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ded9d 
,09-12 08:25:56.778  4285  4301 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,09-12 08:25:56.779  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 08:25:56.780  4285  4301 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 08:25:56.785  4285  4301 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 08:25:56.789  4285  4301 D BluetoothAdapterProperties: Scan Mode:20
,09-12 08:25:56.789  4285  4301 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 08:25:56.790  4285  4301 D bt_hci  : do_postload posting postload work item
09-12 08:25:56.791  4285  4305 I bt_hci  : event_postload
09-12 08:25:56.791  4285  4305 I bt_vendor: sco_config_cb
09-12 08:25:56.791  4285  4305 I bt_hci  : sco_config_callback postload finished.
,09-12 08:25:56.797  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:56.802  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:56.803  4285  4301 D bt_bte_conf: Device ID record 1 : primary
,09-12 08:25:56.804  4285  4301 D bt_bte_conf:   vendorId            = 000f
09-12 08:25:56.804  4285  4301 D bt_bte_conf:   vendorIdSource      = 0001
09-12 08:25:56.804  4285  4301 D bt_bte_conf:   product             = 1200
,09-12 08:25:56.804  4285  4301 D bt_bte_conf:   version             = 1436
09-12 08:25:56.805  4285  4301 D bt_bte_conf:   clientExecutableURL = 
,09-12 08:25:56.805  4285  4301 D bt_bte_conf:   serviceDescription  = 
,09-12 08:25:56.805  4285  4301 D bt_bte_conf:   documentationURL    = 
09-12 08:25:56.805  4285  4301 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 08:25:56.806  4285  4298 D bt_stack_manager: event_start_up_stack finished
,09-12 08:25:56.807  4285  4305 I bt_vendor: low_power_mode_cb
,09-12 08:25:56.807  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 08:25:56.807  4285  4297 D BluetoothAdapterProperties: Setting state to 15
,09-12 08:25:56.808  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 08:25:56.809  4285  4297 I BluetoothAdapterState: Entering BleOnState
09-12 08:25:56.813  4285  4297 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 08:25:56.813  4285  4297 D BluetoothAdapterProperties: Setting state to 11
09-12 08:25:56.813  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 08:25:56.821  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:25:56.824  4285  4285 D HeadsetService: Received start request. Starting profile...
09-12 08:25:56.825  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:56.827  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:56.835  4285  4285 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 08:25:56.836  4285  4285 D HeadsetStateMachine: make
09-12 08:25:56.838  4285  4297 I BluetoothAdapterState: Entering PendingCommandState
,09-12 08:25:56.843  4285  4285 D HeadsetStateMachine: max_hf_connections = 1
,09-12 08:25:56.843  4285  4285 I bt_bluedroid: get_profile_interface handsfree
,09-12 08:25:56.844  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 08:25:56.844  4285  4301 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 08:25:56.849  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:25:56.850  4285  4285 D A2dpService: Received start request. Starting profile...
,09-12 08:25:56.850  4285  4285 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 08:25:56.851  4285  4285 I bt_bluedroid: get_profile_interface avrcp
,09-12 08:25:56.857  4285  4285 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 08:25:56.857  4285  4285 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 08:25:56.858  4285  4285 D A2dpStateMachine: make
,09-12 08:25:56.862  4285  4285 I bt_bluedroid: get_profile_interface a2dp
,09-12 08:25:56.863  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 08:25:56.864  4285  4285 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 08:25:56.865  4285  4316 D A2dpStateMachine: Enter Disconnected: -2
09-12 08:25:56.865  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:25:56.866  4285  4285 D HidService: Received start request. Starting profile...
,09-12 08:25:56.866  4285  4285 I bt_bluedroid: get_profile_interface hidhost
09-12 08:25:56.866  4059  4059 D BluetoothInputDevice: Proxy object connected
09-12 08:25:56.866  4285  4301 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c03e5
09-12 08:25:56.866  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 08:25:56.867  4285  4285 D HidService: setHidService(): set to: null
09-12 08:25:56.867  4059  4059 D HidProfile: Bluetooth service connected
09-12 08:25:56.868  4285  4285 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 08:25:56.869  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:25:56.870  4285  4285 D HealthService: Received start request. Starting profile...
09-12 08:25:56.871  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 08:25:56.871  4285  4285 I bt_bluedroid: get_profile_interface health
09-12 08:25:56.872  4285  4285 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 08:25:56.872  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:25:56.873  4059  4059 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 08:25:56.873  4285  4285 D PanService: Received start request. Starting profile...
,09-12 08:25:56.873  4285  4285 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 08:25:56.873  4285  4285 I bt_bluedroid: get_profile_interface pan
09-12 08:25:56.874  4285  4301 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 08:25:56.874  4059  4059 D PanProfile: Bluetooth service connected
,09-12 08:25:56.878  4285  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:25:56.879  4285  4285 D BluetoothMapService: Received start request. Starting profile...
,09-12 08:25:56.880  4285  4285 D BluetoothMapService: start()
,09-12 08:25:56.880  4059  4059 D BluetoothMap: Proxy object connected
09-12 08:25:56.880  4059  4059 D MapProfile: Bluetooth service connected
09-12 08:25:56.880  4059  4059 D BluetoothMap: getConnectedDevices()
09-12 08:25:56.881  4059  4059 D BluetoothMap: Bluetooth is Not enabled
09-12 08:25:56.882  4285  4285 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 08:25:56.882  4285  4285 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 08:25:56.882  4285  4285 D BluetoothMapAppObserver: createReceiver()
09-12 08:25:56.883  4285  4285 D BluetoothMapAppObserver: initObservers()
09-12 08:25:56.884  4285  4285 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 08:25:56.892  4285  4285 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:25:56.892  4285  4285 V BluetoothAdapterState: isTurningOn()=true
09-12 08:25:56.892  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:56.892  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:56.893  4285  4285 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isTurningOn()=true
09-12 08:25:56.894  4285  4314 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isTurningOff()=false
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isTurningOn()=true
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isTurningOff()=false
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isTurningOn()=true
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:56.894  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:56.895  4285  4285 V BluetoothAdapterState: isTurningOff()=false
09-12 08:25:56.895  4285  4285 V BluetoothAdapterState: isTurningOn()=true
09-12 08:25:56.895  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:56.896  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:56.896  4285  4285 V BluetoothAdapterState: isTurningOff()=false
09-12 08:25:56.896  4285  4285 V BluetoothAdapterState: isTurningOn()=true
,09-12 08:25:56.897  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:56.897  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:25:56.897  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 08:25:56.897  4285  4297 D BluetoothAdapterProperties: ScanMode =  20
,09-12 08:25:56.897  4285  4297 D BluetoothAdapterProperties: State =  11
,09-12 08:25:56.899  4285  4301 D BluetoothAdapterProperties: Scan Mode:21
,09-12 08:25:56.899  4285  4301 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 08:25:56.899  4285  4297 D BluetoothAdapterProperties: Setting state to 12
09-12 08:25:56.899  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 08:25:56.899  4285  4297 I BluetoothAdapterState: Entering OnState
09-12 08:25:56.900  4059  4071 D BluetoothPan: onBluetoothStateChange on: true
09-12 08:25:56.900   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 08:25:56.900   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 08:25:56.900  1362  1374 D BluetoothMap: onBluetoothStateChange: up=true
09-12 08:25:56.903  1362  1362 D BluetoothMap: Proxy object connected
09-12 08:25:56.903  1362  1362 D MapProfile: Bluetooth service connected
09-12 08:25:56.903  1362  1362 D BluetoothMap: getConnectedDevices()
,09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:56.904  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:25:56.904  1362  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 08:25:56.906  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:25:56.906  1362  1362 D BluetoothInputDevice: Proxy object connected
09-12 08:25:56.906  1362  1362 D HidProfile: Bluetooth service connected
09-12 08:25:56.906   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 08:25:56.907  1362  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 08:25:56.908   872   872 D BluetoothA2dp: Proxy object connected
,09-12 08:25:56.910  1953  2123 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 08:25:56.910   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:56.910  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:25:56.911  4285  4285 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 08:25:56.911  4059  4070 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 08:25:56.911  4285  4285 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 08:25:56.912  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 08:25:56.913  4285  4285 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 08:25:56.914  1362  2059 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 08:25:56.914  4285  4285 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 08:25:56.916  4285  4285 D ObexServerSockets: Succeed to create listening sockets 
09-12 08:25:56.916  4285  4285 D ObexServerSockets0: startAccept()
09-12 08:25:56.916  4285  4285 D ObexServerSockets0: prepareForNewConnect()
,09-12 08:25:56.916  1362  1362 D BluetoothA2dp: Proxy object connected
09-12 08:25:56.916  4059  4071 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 08:25:56.917  1362  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 08:25:56.917  4285  4285 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 08:25:56.917  1362  1385 D BluetoothPan: onBluetoothStateChange on: true
09-12 08:25:56.918  4285  4285 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 08:25:56.918  4285  4324 D ObexServerSockets0: Accepting socket connection...
09-12 08:25:56.919  4285  4323 D ObexServerSockets0: Accepting socket connection...
09-12 08:25:56.920  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 08:25:56.920  1362  1362 D PanProfile: Bluetooth service connected
,09-12 08:25:56.921  4059  4070 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 08:25:56.922   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 08:25:56.924  4285  4285 D BluetoothMapService: onReceive
,09-12 08:25:56.924  4285  4285 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 08:25:56.924  4285  4285 D BluetoothMapService: STATE_ON
09-12 08:25:56.924  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:56.925  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:56.927  4059  4059 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-12 08:25:56.930  4059  4059 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 08:25:56.934  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 08:25:56.937  4059  4059 D BluetoothA2dp: Proxy object connected
,09-12 08:25:56.940  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 08:25:56.946  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-12 08:25:56.951  1362  1362 D BluetoothPbap: Proxy object connected
09-12 08:25:56.951  1362  1362 D PbapServerProfile: Bluetooth service connected
09-12 08:25:56.951  4059  4059 D BluetoothPbap: Proxy object connected
,09-12 08:25:56.952  4285  4285 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 08:25:56.952  4285  4285 D ObexServerSockets0: prepareForNewConnect()
09-12 08:25:56.952  4059  4059 D PbapServerProfile: Bluetooth service connected
,09-12 08:25:56.961  4285  4328 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 08:25:56.979  4285  4332 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 08:25:56.980  4285  4332 I BtOppRfcommListener: Accept thread started.
,09-12 08:25:57.002  1953  1967 D BluetoothHeadset: Proxy object connected
,09-12 08:25:57.002   872   872 D BluetoothHeadset: Proxy object connected
09-12 08:25:57.002   872   872 D BluetoothHeadset: Proxy object connected
09-12 08:25:57.003   872   872 D BluetoothHeadset: Proxy object connected
,09-12 08:25:57.003  1362  2059 D BluetoothHeadset: Proxy object connected
09-12 08:25:57.003  1362  1362 D HeadsetProfile: Bluetooth service connected
,09-12 08:25:57.011  1953  2232 D BluetoothHeadset: Proxy object connected
,09-12 08:25:57.011   872   889 D BluetoothHeadset: Proxy object connected
,09-12 08:25:57.017  1362  1385 D BluetoothHeadset: Proxy object connected
,09-12 08:25:57.018  1362  1362 D HeadsetProfile: Bluetooth service connected
,09-12 08:25:57.031  4059  4071 D BluetoothHeadset: Proxy object connected
,09-12 08:25:57.032  4059  4059 D HeadsetProfile: Bluetooth service connected
,09-12 08:25:58.216   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,09-12 08:25:58.280  4285  4297 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 08:25:58.280  4285  4297 D BluetoothAdapterProperties: Setting state to 13
09-12 08:25:58.281  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 08:25:58.283  4285  4297 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 08:25:58.287  4285  4297 I BluetoothAdapterState: Entering PendingCommandState
,09-12 08:25:58.297  4285  4285 D BluetoothMapService: onReceive
,09-12 08:25:58.297  4285  4285 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 08:25:58.297  4285  4285 D BluetoothMapService: STATE_TURNING_OFF
09-12 08:25:58.297  4285  4285 D BluetoothMapService: MAP Service closeService in
,09-12 08:25:58.298  4285  4285 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 08:25:58.298  4285  4285 D ObexServerSockets0: shutdown(block = true)
,09-12 08:25:58.299  4285  4285 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 08:25:58.299  4285  4285 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 08:25:58.299  4285  4324 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-12 08:25:58.300  4285  4309 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 08:25:58.300  4285  4323 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 08:25:58.301  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:58.301  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:25:58.301  4285  4285 I BtOppRfcommListener: stopping Accept Thread
,09-12 08:25:58.302  4285  4332 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 08:25:58.302  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:58.302  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 08:25:58.302  4285  4332 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 08:25:58.306  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:25:58.307  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:25:58.309  3993  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 08:25:58.309  4285  4301 D BluetoothAdapterProperties: Scan Mode:20
,09-12 08:25:58.309  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-12 08:25:58.310  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 08:25:58.311  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 08:25:58.313  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:58.314  4285  4285 D HeadsetService: Received stop request...Stopping profile...
09-12 08:25:58.319  1953  1963 D BluetoothHeadset: Proxy object disconnected
,09-12 08:25:58.320  4285  4285 D A2dpService: Received stop request...Stopping profile...
09-12 08:25:58.320   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 08:25:58.320  4285  4316 D A2dpStateMachine: Exit Disconnected: -1
09-12 08:25:58.320  4059  4071 D BluetoothHeadset: Proxy object disconnected
09-12 08:25:58.320  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:25:58.321   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 08:25:58.321   872   872 D BluetoothHeadset: Proxy object disconnected
09-12 08:25:58.322  1362  1374 D BluetoothHeadset: Proxy object disconnected
,09-12 08:25:58.322   872   872 D BluetoothA2dp: Proxy object disconnected
09-12 08:25:58.323  4285  4285 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:58.323  4285  4285 V BluetoothAdapterState: isTurningOn()=false
,09-12 08:25:58.323  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.323  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:58.326  4285  4285 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 08:25:58.327  4285  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:58.327  4285  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:58.327  4285  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:58.327  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-12 08:25:58.328  4285  4301 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,09-12 08:25:58.328  4285  4285 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 08:25:58.328  4285  4285 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:58.329  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:58.329  4059  4059 D DockEventReceiver: finishStartingService: stopping service
09-12 08:25:58.329  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.329  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:58.330  4059  4059 D HeadsetProfile: Bluetooth service disconnected
,09-12 08:25:58.330  4059  4059 D BluetoothA2dp: Proxy object disconnected
09-12 08:25:58.330  4285  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:58.331  4285  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 08:25:58.331  4285  4307 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 08:25:58.331  4285  4307 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 08:25:58.331  4285  4307 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 08:25:58.331  4285  4307 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 08:25:58.331  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 08:25:58.332  4285  4285 D HidService: Received stop request...Stopping profile...
09-12 08:25:58.332  4285  4285 D HidService: Stopping Bluetooth HidService
,09-12 08:25:58.334  4059  4059 D BluetoothInputDevice: Proxy object disconnected
,09-12 08:25:58.334  4059  4059 D HidProfile: Bluetooth service disconnected
,09-12 08:25:58.336  1362  1362 D BluetoothA2dp: Proxy object disconnected
09-12 08:25:58.337  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-12 08:25:58.337  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,09-12 08:25:58.337  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,09-12 08:25:58.337  1362  1362 D HidProfile: Bluetooth service disconnected
,09-12 08:25:58.338  4285  4285 D HealthService: Received stop request...Stopping profile...
,09-12 08:25:58.340  4285  4285 D PanService: Received stop request...Stopping profile...
,09-12 08:25:58.341  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 08:25:58.341  1362  1362 D PanProfile: Bluetooth service disconnected
,09-12 08:25:58.341  4059  4059 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 08:25:58.341  4059  4059 D PanProfile: Bluetooth service disconnected
09-12 08:25:58.341  4285  4285 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 08:25:58.342  4285  4285 D BluetoothMapService: stop()
09-12 08:25:58.342  4285  4285 D BluetoothMapAppObserver: deinitObservers()
09-12 08:25:58.342  4285  4285 D BluetoothMapAppObserver: removeReceiver()
09-12 08:25:58.343  4059  4059 D BluetoothMap: Proxy object disconnected
09-12 08:25:58.343  1362  1362 D BluetoothMap: Proxy object disconnected
09-12 08:25:58.343  4059  4059 D MapProfile: Bluetooth service disconnected
09-12 08:25:58.343  1362  1362 D MapProfile: Bluetooth service disconnected
09-12 08:25:58.343  4285  4285 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:58.343  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:58.343  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.343  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:58.344  4285  4285 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 08:25:58.344  4285  4301 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 08:25:58.344  4285  4285 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 08:25:58.346  1362  1362 D BluetoothPbap: Proxy object disconnected
09-12 08:25:58.346  1362  1362 D PbapServerProfile: Bluetooth service disconnected
,09-12 08:25:58.346  4059  4059 D BluetoothPbap: Proxy object disconnected
,09-12 08:25:58.346  4059  4059 D PbapServerProfile: Bluetooth service disconnected
09-12 08:25:58.348  4285  4285 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:58.348  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:58.348  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.348  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:58.348  4285  4285 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 08:25:58.348  4285  4301 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 08:25:58.348  4285  4285 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 08:25:58.349  4285  4285 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:58.349  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:58.349  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.349  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:58.349  4285  4285 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 08:25:58.350  4285  4285 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 08:25:58.350  4285  4285 D BluetoothMapService: MAP Service closeService in
09-12 08:25:58.350  4285  4285 V BluetoothAdapterState: isTurningOff()=true
09-12 08:25:58.350  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:58.350  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.351  4285  4285 V BluetoothAdapterState: isBleTurningOff()=false
09-12 08:25:58.351  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 08:25:58.351  4285  4297 D BluetoothAdapterProperties: Setting state to 15
09-12 08:25:58.351  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 08:25:58.352  4285  4297 I BluetoothAdapterState: Entering BleOnState
09-12 08:25:58.352  4285  4285 D BluetoothMapService: cleanup()
09-12 08:25:58.352  4285  4285 D BluetoothMapService: MAP Service closeService in
09-12 08:25:58.352  4059  4070 D BluetoothPan: onBluetoothStateChange on: false
09-12 08:25:58.352   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:58.352   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:58.353  1362  1374 D BluetoothMap: onBluetoothStateChange: up=false
09-12 08:25:58.353  1362  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 08:25:58.354   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 08:25:58.354  4059  4071 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 08:25:58.354  1362  2059 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 08:25:58.355  1953  2123 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:58.355   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:58.355  4059  4070 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 08:25:58.356  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 08:25:58.356  4059  4071 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 08:25:58.357  1362  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:58.357  4059  4070 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 08:25:58.357  1362  2059 D BluetoothPan: onBluetoothStateChange on: false
09-12 08:25:58.357  4059  4071 D BluetoothMap: onBluetoothStateChange: up=false
09-12 08:25:58.358  4285  4297 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 08:25:58.358  4285  4297 D BluetoothAdapterProperties: Setting state to 16
09-12 08:25:58.358  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 08:25:58.358  4285  4297 D BluetoothAdapterProperties: onBleDisable
09-12 08:25:58.359  4285  4297 I BluetoothAdapterState: Entering PendingCommandState
09-12 08:25:58.360  4285  4298 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 08:25:58.361  4285  4307 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 08:25:58.361  4285  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 08:25:58.361  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:58.361  4285  4301 D BluetoothAdapterProperties: Scan Mode:20
09-12 08:25:58.362  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 08:25:58.362  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:58.363  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:58.365  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:25:58.367  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 08:25:58.375  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-12 08:25:58.562  4285  4301 I bt_hci  : shut_down
,09-12 08:25:58.562  4285  4305 D bt_hwcfg: hw_epilog_process
09-12 08:25:58.563  4285  4305 I bt_vendor: low_power_mode_cb
,09-12 08:25:58.586  4285  4305 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 08:25:58.587  4285  4305 I bt_vendor: epilog_cb
09-12 08:25:58.587  4285  4305 I bt_hci  : epilog_finished_callback
,09-12 08:25:58.589  4285  4301 I bt_hci_h4: hal_close
09-12 08:25:58.590  4285  4301 I bt_userial_vendor: device fd = 51 close
,09-12 08:25:58.728  4285  4298 D bt_stack_manager: event_shut_down_stack finished.
,09-12 08:25:58.729  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 08:25:58.734  4285  4297 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 08:25:58.735  4285  4285 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 08:25:58.736  4285  4285 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 08:25:58.737  4285  4285 D BtGatt.GattService: stop()
09-12 08:25:58.737  4285  4285 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 08:25:58.742  4285  4285 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:25:58.743  4285  4285 V BluetoothAdapterState: isTurningOn()=false
09-12 08:25:58.743  4285  4285 V BluetoothAdapterState: isBleTurningOn()=false
09-12 08:25:58.743  4285  4285 V BluetoothAdapterState: isBleTurningOff()=true
09-12 08:25:58.744  4285  4297 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 08:25:58.745  4285  4297 D BluetoothAdapterProperties: Setting state to 10
09-12 08:25:58.745  4285  4297 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 08:25:58.747  4285  4297 I BluetoothAdapterState: Entering OffState
09-12 08:25:58.749   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 08:25:58.779  4285  4285 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...,
,09-12 08:25:58.780  4285  4285 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-12 08:25:58.780  4285  4298 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 08:25:58.789  4285  4285 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 08:25:58.791  4285  4298 D bt_stack_manager: event_clean_up_stack finished.
,09-12 08:25:58.797  4285  4285 I art     : System.exit called, status: 0
,09-12 08:25:58.797  4285  4285 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 08:25:58.857   872  2226 I ActivityManager: Process com.android.bluetooth (pid 4285) has died
,09-12 08:26:01.277  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 08:26:01.277  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:26:03.585   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 08:26:03.596  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-12 08:26:03.612   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437,
09-12 08:26:03.612   872   892 I Adreno  : Build Date                       : 10/20/15
09-12 08:26:03.612   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 08:26:03.612   872   892 I Adreno  : Local Branch                     : M14
09-12 08:26:03.612   872   892 I Adreno  : Remote Branch                    : 
09-12 08:26:03.612   872   892 I Adreno  : Remote Branch                    : 
09-12 08:26:03.612   872   892 I Adreno  : Reconstruct Branch               : 
,09-12 08:26:03.653   280   348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (315 us)
,09-12 08:26:04.285  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 08:26:04.286  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e7f8d8 added. We now have 6 listener(s)
09-12 08:26:04.286  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:26:04.293  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 08:26:04.293  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a6f431 added. We now have 7 listener(s)
09-12 08:26:04.293  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:04.295  3993  4042 I System.out: IsBluetoothEnabled
,09-12 08:26:04.340  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 08:26:04.340  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 08:26:04.375   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 08:26:04.379  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6f56f7e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9631716, 16908290=android.view.AbsSavedState$1@9631716}, android:focusedViewId=100}]}]
,09-12 08:26:04.380  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-12 08:26:04.381  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 08:26:04.383  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 08:26:04.394  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:04.400   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 08:26:04.408   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-12 08:26:04.408   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-12 08:26:04.409   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF,
,09-12 08:26:04.416   872   889 I ActivityManager: Start proc 4344:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 08:26:04.470  4344  4344 D AdapterServiceConfig: Adding HeadsetService
,09-12 08:26:04.470  4344  4344 D AdapterServiceConfig: Adding A2dpService
09-12 08:26:04.470  4344  4344 D AdapterServiceConfig: Adding HidService
09-12 08:26:04.470  4344  4344 D AdapterServiceConfig: Adding HealthService
09-12 08:26:04.470  4344  4344 D AdapterServiceConfig: Adding PanService
09-12 08:26:04.471  4344  4344 D AdapterServiceConfig: Adding GattService
09-12 08:26:04.471  4344  4344 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 08:26:04.479   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c9404a:true
,09-12 08:26:04.479  4344  4344 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 08:26:04.483  4344  4344 I bt_bluedroid: init
,09-12 08:26:04.484  4344  4356 I BluetoothAdapterState: Entering OffState
,09-12 08:26:04.488  4344  4357 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 08:26:04.488  4344  4357 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 08:26:04.488  4344  4357 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 08:26:04.489  4344  4357 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 08:26:04.490  4344  4344 I bt_bluedroid: get_profile_interface socket
,09-12 08:26:04.492  4344  4360 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 08:26:04.492  4344  4344 I bt_bluedroid: get_profile_interface sdp
09-12 08:26:04.493  4344  4360 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 08:26:04.495  4344  4355 I bt_bluedroid: config_hci_snoop_log
,09-12 08:26:04.496   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 08:26:04.503  4344  4356 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 08:26:04.504  4344  4356 D BluetoothAdapterProperties: Setting state to 14
,09-12 08:26:04.504  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 08:26:04.507  4344  4356 D BluetoothBondStateMachine: make
,09-12 08:26:04.512  4344  4361 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 08:26:04.520  4344  4356 I BluetoothAdapterState: Entering PendingCommandState
,09-12 08:26:04.520  4344  4344 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 08:26:04.525  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:26:04.526  4344  4344 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 08:26:04.527  4344  4344 D BtGatt.GattService: Received start request. Starting profile...
,09-12 08:26:04.527  4344  4344 D BtGatt.GattService: start()
09-12 08:26:04.527  4344  4344 I bt_bluedroid: get_profile_interface gatt
,09-12 08:26:04.529  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:26:04.530  4344  4344 D BtGatt.AdvertiseManager: advertise manager created
,09-12 08:26:04.541  4344  4344 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:26:04.542  4344  4344 V BluetoothAdapterState: isTurningOn()=false
09-12 08:26:04.542  4344  4344 V BluetoothAdapterState: isBleTurningOn()=true
09-12 08:26:04.542  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:26:04.543  4344  4356 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 08:26:04.544  4344  4356 I bt_bluedroid: enable
,09-12 08:26:04.544  4344  4357 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 08:26:04.545  4344  4357 I bt_hci  : start_up
,09-12 08:26:04.556  4344  4357 I bt_vendor: alloc value 0xb3a61189
,09-12 08:26:04.556  4344  4357 I bt_vendor: init
09-12 08:26:04.556  4344  4357 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 08:26:04.556  4344  4357 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 08:26:04.638   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-12 08:26:04.640   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 08:26:04.647   872  1330 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,09-12 08:26:04.651   872   892 I DreamManagerService: Entering dreamland.
09-12 08:26:04.652   872   892 I PowerManagerService: Dozing...
,09-12 08:26:04.653   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 08:26:04.663  4344  4357 D bt_hci  : start_up starting async portion
,09-12 08:26:04.663  4344  4364 I bt_hci  : event_finish_startup
,09-12 08:26:04.663  4344  4364 I bt_hci_h4: hal_open
,09-12 08:26:04.664  4344  4364 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 08:26:04.670  4344  4364 I bt_userial_vendor: device fd = 51 open
,09-12 08:26:04.702   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 08:26:04.702   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 08:26:04.707  4344  4364 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 08:26:04.707   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:26:04.713   872  1307 E native  : do suspend false
,09-12 08:26:04.721  1939  4367 D NfcService: Discovery configuration equal, not updating.
,09-12 08:26:04.739  4344  4364 D bt_hwcfg: Chipset BCM4354A2
,09-12 08:26:04.739  4344  4364 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 08:26:04.740  4344  4364 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 08:26:04.763   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:26:04.772   872  1307 E native  : do suspend true
,09-12 08:26:04.841   375  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 08:26:04.841   375  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 08:26:05.570  4344  4364 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-12 08:26:05.571  4344  4364 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 08:26:05.571  4344  4364 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 08:26:05.689  4344  4364 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-12 08:26:05.690  4344  4364 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 08:26:05.719  4344  4364 I bt_hwcfg: vendor lib fwcfg completed
,09-12 08:26:05.719  4344  4364 I bt_vendor: firmware callback
09-12 08:26:05.720  4344  4364 I bt_hci  : firmware_config_callback
,09-12 08:26:05.734  4344  4371 I bt_btu  : btu_task pending for preload complete event
,09-12 08:26:05.734  4344  4371 I bt_btu_task: Bluetooth chip preload is complete
,09-12 08:26:05.734  4344  4371 I bt_btu  : btu_task received preload complete event
,09-12 08:26:05.744  4344  4371 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 08:26:05.744  4344  4371 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 08:26:05.745  4344  4371 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 08:26:05.745  4344  4371 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 08:26:05.745  4344  4371 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 08:26:05.745  4344  4371 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 08:26:05.746  4344  4371 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 08:26:05.746  4344  4371 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 08:26:05.746  4344  4371 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 08:26:05.746  4344  4371 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 08:26:05.747  4344  4371 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 08:26:05.747  4344  4371 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 08:26:05.747  4344  4371 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 08:26:05.747  4344  4371 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 08:26:05.748  4344  4371 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 08:26:05.896  4344  4371 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ded9d
,09-12 08:26:05.896  4344  4371 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ded9d 
,09-12 08:26:05.908  4344  4360 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 08:26:05.910  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 08:26:05.910  4344  4360 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 08:26:05.914  4344  4360 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 08:26:05.918  4344  4360 D BluetoothAdapterProperties: Scan Mode:20
09-12 08:26:05.918  4344  4360 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 08:26:05.918  4344  4360 D bt_hci  : do_postload posting postload work item
09-12 08:26:05.918  4344  4364 I bt_hci  : event_postload
09-12 08:26:05.919  4344  4364 I bt_vendor: sco_config_cb
09-12 08:26:05.919  4344  4364 I bt_hci  : sco_config_callback postload finished.
,09-12 08:26:05.922  4344  4360 D bt_bte_conf: Device ID record 1 : primary
09-12 08:26:05.922  4344  4360 D bt_bte_conf:   vendorId            = 000f
09-12 08:26:05.922  4344  4360 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 08:26:05.922  4344  4360 D bt_bte_conf:   product             = 1200
,09-12 08:26:05.922  4344  4360 D bt_bte_conf:   version             = 1436
,09-12 08:26:05.923  4344  4360 D bt_bte_conf:   clientExecutableURL = 
,09-12 08:26:05.923  4344  4360 D bt_bte_conf:   serviceDescription  = 
,09-12 08:26:05.923  4344  4360 D bt_bte_conf:   documentationURL    = 
,09-12 08:26:05.923  4344  4360 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 08:26:05.924  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:05.924  4344  4357 D bt_stack_manager: event_start_up_stack finished
,09-12 08:26:05.927  4344  4356 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 08:26:05.927  4344  4356 D BluetoothAdapterProperties: Setting state to 15
,09-12 08:26:05.927  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 08:26:05.928  4344  4356 I BluetoothAdapterState: Entering BleOnState,
09-12 08:26:05.932  4344  4364 I bt_vendor: low_power_mode_cb
,09-12 08:26:05.933  4344  4356 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 08:26:05.934  4344  4356 D BluetoothAdapterProperties: Setting state to 11
09-12 08:26:05.934  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 08:26:05.943  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:05.947  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:26:05.948  4344  4344 D HeadsetService: Received start request. Starting profile...,
,09-12 08:26:05.952  4344  4344 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 08:26:05.952  4344  4344 D HeadsetStateMachine: make
,09-12 08:26:05.963  4344  4356 I BluetoothAdapterState: Entering PendingCommandState
,09-12 08:26:05.969  4344  4344 D HeadsetStateMachine: max_hf_connections = 1
,09-12 08:26:05.969  4344  4344 I bt_bluedroid: get_profile_interface handsfree
09-12 08:26:05.969  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 08:26:05.970  4344  4360 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-12 08:26:05.974  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:26:05.974  4344  4344 D A2dpService: Received start request. Starting profile...
,09-12 08:26:05.974  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 08:26:05.975  4344  4344 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 08:26:05.975  4344  4344 I bt_bluedroid: get_profile_interface avrcp
,09-12 08:26:05.981  4344  4344 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 08:26:05.981  4344  4344 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 08:26:05.981  4344  4344 D A2dpStateMachine: make
,09-12 08:26:05.983  4344  4344 I bt_bluedroid: get_profile_interface a2dp
09-12 08:26:05.983  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 08:26:05.985  4344  4385 D A2dpStateMachine: Enter Disconnected: -2
,09-12 08:26:05.986  4344  4344 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 08:26:05.987  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
09-12 08:26:05.987  4344  4344 D HidService: Received start request. Starting profile...
09-12 08:26:05.988  4344  4344 I bt_bluedroid: get_profile_interface hidhost
,09-12 08:26:05.988  4344  4360 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c03e5
09-12 08:26:05.988  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 08:26:05.988  4344  4344 D HidService: setHidService(): set to: null
,09-12 08:26:05.989  4344  4344 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 08:26:05.989  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:26:05.990  4344  4344 D HealthService: Received start request. Starting profile...
,09-12 08:26:05.991  4344  4344 I bt_bluedroid: get_profile_interface health
09-12 08:26:05.992  4344  4344 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 08:26:05.993  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:26:05.993  4344  4344 D PanService: Received start request. Starting profile...
09-12 08:26:05.994  4344  4344 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 08:26:05.994  4344  4344 I bt_bluedroid: get_profile_interface pan
,09-12 08:26:05.994  4344  4360 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 08:26:05.997  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:26:05.997  4344  4344 D BluetoothMapService: Received start request. Starting profile...
09-12 08:26:05.997  4344  4344 D BluetoothMapService: start()
,09-12 08:26:06.000  4344  4344 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 08:26:06.000  4344  4344 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 08:26:06.000  4344  4344 D BluetoothMapAppObserver: createReceiver()
,09-12 08:26:06.001  4344  4344 D BluetoothMapAppObserver: initObservers()
09-12 08:26:06.001  4344  4344 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 08:26:06.008  4344  4344 V BluetoothAdapterState: isTurningOff()=false
09-12 08:26:06.008  4344  4344 V BluetoothAdapterState: isTurningOn()=true
09-12 08:26:06.009  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 08:26:06.009  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:26:06.011  4344  4383 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 08:26:06.012  4344  4344 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isTurningOn()=true
09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isTurningOn()=true
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false,
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isTurningOn()=true
09-12 08:26:06.013  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 08:26:06.014  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:26:06.014  4344  4344 V BluetoothAdapterState: isTurningOff()=false,
,09-12 08:26:06.014  4344  4344 V BluetoothAdapterState: isTurningOn()=true
,09-12 08:26:06.014  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 08:26:06.015  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:26:06.016  4344  4344 V BluetoothAdapterState: isTurningOff()=false
,09-12 08:26:06.016  4344  4344 V BluetoothAdapterState: isTurningOn()=true
,09-12 08:26:06.016  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 08:26:06.016  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 08:26:06.017  4344  4356 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2,
09-12 08:26:06.017  4344  4356 D BluetoothAdapterProperties: ScanMode =  20
,09-12 08:26:06.017  4344  4356 D BluetoothAdapterProperties: State =  11
,09-12 08:26:06.018  4344  4356 D BluetoothAdapterProperties: Setting state to 12
,09-12 08:26:06.018  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 08:26:06.018  4344  4356 I BluetoothAdapterState: Entering OnState
,09-12 08:26:06.018  4059  4071 D BluetoothPan: onBluetoothStateChange on: true
,09-12 08:26:06.019  4344  4360 D BluetoothAdapterProperties: Scan Mode:21
09-12 08:26:06.019  4344  4360 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 08:26:06.022   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 08:26:06.022   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 08:26:06.022  1362  2059 D BluetoothMap: onBluetoothStateChange: up=true
09-12 08:26:06.023  4059  4059 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 08:26:06.023  4059  4059 D PanProfile: Bluetooth service connected
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:26:06.024  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:26:06.025  1362  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 08:26:06.026  1362  1362 D BluetoothMap: Proxy object connected
09-12 08:26:06.026  1362  1362 D MapProfile: Bluetooth service connected
,09-12 08:26:06.026  1362  1362 D BluetoothMap: getConnectedDevices()
09-12 08:26:06.026  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:26:06.027   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 08:26:06.028  4344  4344 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 08:26:06.028  4059  4071 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 08:26:06.029  4344  4344 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 08:26:06.030  4344  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 08:26:06.031  1362  2059 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 08:26:06.033  1953  1963 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 08:26:06.033  4344  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 08:26:06.034   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 08:26:06.034  4059  4070 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 08:26:06.035  4344  4344 D ObexServerSockets: Succeed to create listening sockets 
09-12 08:26:06.035  4344  4344 D ObexServerSockets0: startAccept()
,09-12 08:26:06.035  4344  4344 D ObexServerSockets0: prepareForNewConnect()
09-12 08:26:06.036  1362  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 08:26:06.037  4344  4344 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 08:26:06.037  4344  4344 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 08:26:06.039  4344  4390 D ObexServerSockets0: Accepting socket connection...
09-12 08:26:06.039  1362  1362 D BluetoothInputDevice: Proxy object connected
09-12 08:26:06.039  1362  1362 D HidProfile: Bluetooth service connected
09-12 08:26:06.040   872   872 D BluetoothA2dp: Proxy object connected
,09-12 08:26:06.040  4344  4391 D ObexServerSockets0: Accepting socket connection...
09-12 08:26:06.040  4059  4071 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 08:26:06.041  4059  4059 D BluetoothA2dp: Proxy object connected
,09-12 08:26:06.042  1362  1362 D BluetoothA2dp: Proxy object connected
09-12 08:26:06.043  1362  2059 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 08:26:06.044  4059  4070 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 08:26:06.044  1362  1374 D BluetoothPan: onBluetoothStateChange on: true
,09-12 08:26:06.046  4059  4071 D BluetoothMap: onBluetoothStateChange: up=true
09-12 08:26:06.046  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 08:26:06.047  1362  1362 D PanProfile: Bluetooth service connected
,09-12 08:26:06.049  4059  4059 D BluetoothInputDevice: Proxy object connected
09-12 08:26:06.049  4059  4059 D HidProfile: Bluetooth service connected
,09-12 08:26:06.050   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 08:26:06.051  4344  4344 D BluetoothMapService: onReceive
,09-12 08:26:06.051  4344  4344 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 08:26:06.051  4344  4344 D BluetoothMapService: STATE_ON
,09-12 08:26:06.052  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:26:06.054  4059  4059 D BluetoothMap: Proxy object connected
09-12 08:26:06.054  4059  4059 D MapProfile: Bluetooth service connected
,09-12 08:26:06.054  4059  4059 D BluetoothMap: getConnectedDevices()
09-12 08:26:06.062  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 08:26:06.071  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 08:26:06.080  4344  4344 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 08:26:06.080  4344  4344 D ObexServerSockets0: prepareForNewConnect()
09-12 08:26:06.080  1362  1362 D BluetoothPbap: Proxy object connected
,09-12 08:26:06.080  1362  1362 D PbapServerProfile: Bluetooth service connected
,09-12 08:26:06.084  4059  4059 D DockEventReceiver: finishStartingService: stopping service
09-12 08:26:06.084  4059  4059 D BluetoothPbap: Proxy object connected
09-12 08:26:06.084  4059  4059 D PbapServerProfile: Bluetooth service connected
,09-12 08:26:06.097  4344  4397 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 08:26:06.118  4344  4401 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 08:26:06.121  4344  4401 I BtOppRfcommListener: Accept thread started.
,09-12 08:26:06.126  1953  2123 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.126   872   872 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.126  4059  4392 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.126  4059  4059 D HeadsetProfile: Bluetooth service connected
09-12 08:26:06.127   872   872 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.127   872   872 D BluetoothHeadset: Proxy object connected
09-12 08:26:06.127  1362  2059 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.128  1362  1362 D HeadsetProfile: Bluetooth service connected
09-12 08:26:06.134  1953  1967 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.134   872   889 D BluetoothHeadset: Proxy object connected
,09-12 08:26:06.144  1362  1374 D BluetoothHeadset: Proxy object connected
09-12 08:26:06.144  1362  1362 D HeadsetProfile: Bluetooth service connected
,09-12 08:26:06.145  4059  4071 D BluetoothHeadset: Proxy object connected
09-12 08:26:06.145  4059  4059 D HeadsetProfile: Bluetooth service connected
,09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:26:06.424  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:26:06.433  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:26:06.436  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 08:26:06.436  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13db897 added. We now have 8 listener(s)
09-12 08:26:06.437  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:26:06.444   872  1968 D WifiService: setWifiEnabled: false pid=3993, uid=10000
,09-12 08:26:06.444   872  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 08:26:06.459  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:06.460   872  2225 D WifiService: setWifiEnabled: true pid=3993, uid=10000
09-12 08:26:06.461   872  2225 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 08:26:06.477   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:26:06.494  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:26:06.502  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:26:06.520   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-12 08:26:06.521   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 08:26:06.522   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 08:26:06.522   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 08:26:06.523   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 08:26:06.523   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 08:26:06.523   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 08:26:06.540   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 08:26:06.541   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,09-12 08:26:06.542   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 08:26:06.542   371   870 D CommandListener: Setting iface cfg
,09-12 08:26:06.543   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-12 08:26:06.543   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 08:26:06.546   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 08:26:06.547   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 08:26:06.569   872  1307 E native  : do suspend true
,09-12 08:26:06.602   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 08:26:06.602   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 08:26:06.616   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 08:26:06.701   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 08:26:06.705  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 08:26:07.143  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 08:26:07.186  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 08:26:07.186  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 08:26:07.193   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:26:07.209   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 08:26:07.210   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 08:26:07.210   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 08:26:07.234   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 08:26:07.256   371   870 D CommandListener: Setting iface cfg
,09-12 08:26:07.258   872  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 08:26:07.274   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 08:26:07.290   872  4409 D DhcpClient: Receive thread started
,09-12 08:26:07.377   872  1307 E native  : do suspend false
,09-12 08:26:07.397   872  1895 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 08:26:07.409   872  4409 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,09-12 08:26:07.410   872  1895 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,09-12 08:26:07.411   872  1895 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 08:26:07.425   872  4409 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 08:26:07.426   872  1895 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 08:26:07.428   371   870 D CommandListener: Setting iface cfg
09-12 08:26:07.434   872  1895 D DhcpClient: Scheduling renewal in 86399s
,09-12 08:26:07.437   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 08:26:07.439   872  1307 E native  : do suspend true
,09-12 08:26:07.464   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 08:26:07.467   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 08:26:07.469   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 08:26:07.470   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 08:26:07.479   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 08:26:07.487  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 08:26:07.491  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 08:26:07.495  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 08:26:07.495  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 08:26:07.498  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6f56f7e Bundle[{}]
,09-12 08:26:07.498  3993  4042 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 08:26:07.498  3993  4042 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 08:26:07.499  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 08:26:07.499  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 08:26:07.500  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 08:26:07.500  3993  4042 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 08:26:07.505  3993  4042 I System.out: Running OutgoingSocketThread
,09-12 08:26:07.506  3993  4412 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 467)
,09-12 08:26:07.507  3993  4412 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44994
,09-12 08:26:07.507  3993  4412 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 08:26:07.511   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 08:26:07.511   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 08:26:07.512   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 08:26:07.513   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 08:26:07.514   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 08:26:07.518   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:26:07.522   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-12 08:26:07.522   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 08:26:07.522   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 08:26:07.523   872  1309 D ConnectivityService:    accepting network in place of null
,09-12 08:26:07.523   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 08:26:07.524   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 08:26:07.524   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 08:26:07.539   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154243, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 08:26:07.547   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:26:07.571   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 08:26:07.574   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 08:26:07.574   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:26:07.575   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-12 08:26:07.577   872   889 D Tethering: MasterInitialState.processMessage what=3
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:26:07.586  3993  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:26:07.589  3993  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:26:07.597  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 08:26:07.600  1725  1725 D SystemUpdateService: onCreate
,09-12 08:26:07.603   872  4407 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-12 08:26:07.607  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 08:26:07.618  1725  4419 I SystemUpdateService: active receiver: enabled
,09-12 08:26:07.626  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 08:26:07.633  1725  2466 I iu.UploadsManager: num queued entries: 0
,09-12 08:26:07.634  1725  2466 I iu.UploadsManager: num updated entries: 0
,09-12 08:26:07.636  1725  4419 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 08:26:07.638  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 08:26:07.640  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 08:26:07.642  4140  4140 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 08:26:07.646  1725  4422 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 08:26:07.646  1725  4422 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 08:26:07.647  4140  4140 D SprintDMHelper: simOperator: 
,09-12 08:26:07.647  4140  4140 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 08:26:07.651  1725  4422 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 08:26:07.657  1725  4419 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 08:26:07.657  1725  4419 I SystemUpdateService: now status is 0 (complete)
09-12 08:26:07.657  1725  4419 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 08:26:07.657  1725  4419 I SystemUpdateService: file has been verified
09-12 08:26:07.657  1725  4419 I SystemUpdateService: OTA package size = 12249756
,09-12 08:26:07.662   872  4407 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 06:26:07 GMT], X-Android-Received-Millis=[1473661567662], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473661567639]}
09-12 08:26:07.662  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:07.664   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-12 08:26:07.664   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 08:26:07.665   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:26:07.666  1725  2466 I iu.SyncManager: NEXT; no task
09-12 08:26:07.667   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 08:26:07.668  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:07.680  1725  4419 I SystemUpdateService: showing system update notification
,09-12 08:26:07.714  1725  1725 D SystemUpdateService: onDestroy
,09-12 08:26:07.717  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 08:26:07.717  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 08:26:07.717  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:07.718  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:07.742  1725  4422 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-12 08:26:07.761  2861  4424 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 08:26:08.508  3993  4042 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 468)
09-12 08:26:08.508  3993  4042 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 468)
,09-12 08:26:08.518  3993  4042 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 473)
,09-12 08:26:08.520  3993  4042 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 08:26:08.520  3993  4042 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 474)
,09-12 08:26:08.525  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 08:26:08.525  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14fca84 added. We now have 2 listener(s)
,09-12 08:26:08.527  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 08:26:08.527  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:26:08.527  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 08:26:08.527  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.528  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c5a26d added. We now have 9 listener(s)
09-12 08:26:08.528  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:26:08.528  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 08:26:08.531  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:26:08.538  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:26:08.541  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:26:08.541  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 08:26:08.543  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 08:26:08.543  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b4733 added. We now have 3 listener(s)
,09-12 08:26:08.544  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:08.546  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:08.549  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
09-12 08:26:08.549  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:26:08.549  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 08:26:08.550  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 08:26:08.550  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9410af0 added. We now have 10 listener(s)
09-12 08:26:08.550  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:26:08.551  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:26:08.551  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:26:08.551  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:26:08.552  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.552  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.552  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:26:08.553  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.554  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14fca84 removed from the list
09-12 08:26:08.554  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.554  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c5a26d removed from the list
09-12 08:26:08.554  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:26:08.554  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.555  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.556  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.557  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.558  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.558  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.558  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c5a26d not in the list
09-12 08:26:08.558  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.559  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.561  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.561  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.561  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:26:08.561  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9410af0 removed from the list
,09-12 08:26:08.562  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.562  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:26:08.562  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:26:08.562  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.563  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b4733 removed from the list,
,09-12 08:26:08.565  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 08:26:08.565  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a6f869 added. We now have 2 listener(s)
,09-12 08:26:08.570  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 08:26:08.571  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 08:26:08.571  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 08:26:08.572  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.572  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfdf2ee added. We now have 9 listener(s)
,09-12 08:26:08.572  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:26:08.574   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 08:26:08.575  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 08:26:08.577  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:26:08.584  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:26:08.587  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:26:08.587  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 08:26:08.588  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 08:26:08.589  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c3e61c added. We now have 3 listener(s)
,09-12 08:26:08.590  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:26:08.592  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:08.594  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 08:26:08.595  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:26:08.595  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 08:26:08.596  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 08:26:08.596  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2db225 added. We now have 10 listener(s)
,09-12 08:26:08.597  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:08.597  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:26:08.597  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-12 08:26:08.597  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 08:26:08.598  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:26:08.598  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 08:26:08.604  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 08:26:08.605  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 08:26:08.613  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 08:26:08.614  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 08:26:08.615  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 08:26:08.620  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 08:26:08.620  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 08:26:08.620  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 08:26:08.621  3993  4042 D BluetoothAdapter: STATE_ON
,09-12 08:26:08.625  4344  4355 D BtGatt.GattService: registerClient() - UUID=95ae7bd8-4c6d-4b97-948a-c0dc3516cd66
,09-12 08:26:08.626  4344  4360 D BtGatt.GattService: onClientRegistered() - UUID=95ae7bd8-4c6d-4b97-948a-c0dc3516cd66, clientIf=5
,09-12 08:26:08.627  3993  4005 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 08:26:08.628  4344  4354 D BtGatt.GattService: start scan with filters
,09-12 08:26:08.632  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 08:26:08.632  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 08:26:08.632  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 08:26:08.633  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 08:26:08.634  4344  4363 D BtGatt.ScanManager: handling starting scan
,09-12 08:26:08.636  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 08:26:08.636  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 08:26:08.637  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 08:26:08.638  4344  4363 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a376232
,09-12 08:26:08.638  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 08:26:08.642  3993  4042 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 08:26:08.642  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 08:26:08.643  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 08:26:08.643  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:26:08.643  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 08:26:08.643  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 08:26:08.643  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 08:26:08.643  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 08:26:08.643  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 08:26:08.644  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 08:26:08.644  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 08:26:08.645  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:26:08.645  4344  4355 D BtGatt.GattService: stopScan() - queue size =1
,09-12 08:26:08.646  4344  4354 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 08:26:08.646  4344  4360 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 08:26:08.646  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.646  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 08:26:08.647  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 08:26:08.647  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 08:26:08.647  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 08:26:08.647  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 08:26:08.647  4344  4363 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 08:26:08.648  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:26:08.648  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 08:26:08.648  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 08:26:08.649  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 08:26:08.649  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 08:26:08.650  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 08:26:08.650  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 08:26:08.651  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 08:26:08.654  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:26:08.654  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:26:08.654  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:26:08.654  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.654  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.654  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:26:08.654  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.654  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a6f869 removed from the list
09-12 08:26:08.655  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.655  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfdf2ee removed from the list
09-12 08:26:08.655  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:26:08.655  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.655  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.655  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.659  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.659  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.659  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.659  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfdf2ee not in the list
09-12 08:26:08.660  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.660  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.661  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.661  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.661  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.661  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2db225 removed from the list
09-12 08:26:08.661  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.661  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.661  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.661  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.661  3993  4042 V org.thaliproject.p2p.btconnectorlib.Connectio,nManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c3e61c removed from the list
,09-12 08:26:08.663  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 08:26:08.663  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ac4ba1 added. We now have 2 listener(s)
09-12 08:26:08.665  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 08:26:08.665  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 08:26:08.665  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 08:26:08.665  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.665  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed71c6 added. We now have 9 listener(s)
,09-12 08:26:08.665  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:08.666  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 08:26:08.671  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 08:26:08.671  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:26:08.671  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:26:08.672  4344  4363 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 08:26:08.672  4344  4363 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:26:08.676  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:26:08.679  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:26:08.679  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 08:26:08.680  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 08:26:08.680  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efcdcb4 added. We now have 3 listener(s)
,09-12 08:26:08.682  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:08.683  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 08:26:08.683  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:26:08.683  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 08:26:08.683  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 08:26:08.683  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42100dd added. We now have 10 listener(s)
,09-12 08:26:08.684  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 08:26:08.684  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:26:08.684  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:26:08.685  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 08:26:08.685  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 08:26:08.685  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 08:26:08.686  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:26:08.686  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 08:26:08.686  4344  4360 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 08:26:08.686  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.690  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 08:26:08.690  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 08:26:08.693  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 08:26:08.693  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.693  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 08:26:08.694  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 08:26:08.694  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 08:26:08.698  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 08:26:08.698  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 08:26:08.698  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 08:26:08.698  3993  4042 D BluetoothAdapter: STATE_ON
,09-12 08:26:08.700  4344  4382 D BtGatt.GattService: registerClient() - UUID=770e5e0a-239b-46c2-8e22-dadb213b31d6
,09-12 08:26:08.701  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 08:26:08.701  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.701  4344  4360 D BtGatt.GattService: onClientRegistered() - UUID=770e5e0a-239b-46c2-8e22-dadb213b31d6, clientIf=5
09-12 08:26:08.701  4344  4363 D BtGatt.ScanManager: stopping BLe Batch
09-12 08:26:08.701  3993  4004 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 08:26:08.701  4344  4393 D BtGatt.GattService: start scan with filters
,09-12 08:26:08.704  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 08:26:08.704  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 08:26:08.704  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 08:26:08.704  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 08:26:08.707  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 08:26:08.707  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.707  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:26:08.707  4344  4363 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 08:26:08.707  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 08:26:08.707  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:26:08.709  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 08:26:08.711  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 08:26:08.711  3993  4042 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 08:26:08.712  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:26:08.712  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:26:08.712  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:26:08.712  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.712  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.712  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 08:26:08.712  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.712  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ac4ba1 removed from the list
,09-12 08:26:08.712  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.712  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed71c6 removed from the list
09-12 08:26:08.712  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 08:26:08.712  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:26:08.713  4344  4360 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 08:26:08.713  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.713  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.713  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 08:26:08.713  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:26:08.713  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 08:26:08.714  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.714  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.714  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.714  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed71c6 not in the list
09-12 08:26:08.714  4344  4363 D BtGatt.ScanManager: handling starting scan
09-12 08:26:08.714  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 08:26:08.714  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 08:26:08.714  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 08:26:08.714  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 08:26:08.714  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 08:26:08.715  3993  4042 D BluetoothAdapter: STATE_ON
09-12 08:26:08.715  4344  4393 D BtGatt.GattService: stopScan() - queue size =1
,09-12 08:26:08.716  4344  4355 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 08:26:08.716  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 08:26:08.716  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 08:26:08.716  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 08:26:08.716  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 08:26:08.716  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 08:26:08.717  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 08:26:08.717  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 08:26:08.717  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 08:26:08.717  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 08:26:08.718  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:26:08.719  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.719  4344  4360 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 08:26:08.720  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.719  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.720  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.720  4344  4363 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 08:26:08.720  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:26:08.720  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42100dd removed from the list
09-12 08:26:08.720  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.720  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:26:08.720  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.720  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.720  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 08:26:08.720  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.720  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efcdcb4 removed from the list
09-12 08:26:08.721  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 08:26:08.721  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@731cdd9 added. We now have 2 listener(s)
09-12 08:26:08.722  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 08:26:08.722  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:26:08.722  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 08:26:08.723  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.723  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc2f39e added. We now have 9 listener(s)
09-12 08:26:08.723  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:08.723  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 08:26:08.725  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 08:26:08.725  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.725  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:26:08.725  4344  4363 D BtGatt.ScanManager: Starting BLE batch scan
09-12 08:26:08.725  4344  4363 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:26:08.728  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:26:08.730  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:26:08.730  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 08:26:08.730  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 08:26:08.730  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b0e4c added. We now have 3 listener(s)
,09-12 08:26:08.732  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 08:26:08.732  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 08:26:08.732  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 08:26:08.733  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.733  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e86e95 added. We now have 10 listener(s)
09-12 08:26:08.733  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:08.733  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:26:08.733  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:08.733  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 08:26:08.733  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 08:26:08.733  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:26:08.733  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 08:26:08.735  4344  4360 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 08:26:08.735  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.735  3993  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 08:26:08.736  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 08:26:08.736  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 08:26:08.738  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 08:26:08.739  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 08:26:08.739  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 08:26:08.740  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 08:26:08.740  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:26:08.742  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 08:26:08.742  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 08:26:08.742  3993  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 08:26:08.743  3993  4042 D BluetoothAdapter: STATE_ON
,09-12 08:26:08.745  4344  4382 D BtGatt.GattService: registerClient() - UUID=f352c632-2b47-4c2b-baf3-b16c34c363e7
,09-12 08:26:08.745  4344  4360 D BtGatt.GattService: onClientRegistered() - UUID=f352c632-2b47-4c2b-baf3-b16c34c363e7, clientIf=5
09-12 08:26:08.745  3993  4005 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 08:26:08.745  4344  4393 D BtGatt.GattService: start scan with filters
,09-12 08:26:08.747  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 08:26:08.747  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.747  4344  4363 D BtGatt.ScanManager: stopping BLe Batch
,09-12 08:26:08.748  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 08:26:08.748  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 08:26:08.748  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 08:26:08.748  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 08:26:08.751  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 08:26:08.751  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 08:26:08.751  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 08:26:08.752  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 08:26:08.753  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 08:26:08.753  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:26:08.754  4344  4363 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 08:26:08.759  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 08:26:08.759  4344  4360 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 08:26:08.759  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:26:08.759  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.759  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:26:08.759  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 08:26:08.759  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.760  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 08:26:08.760  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 08:26:08.760  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@731cdd9 removed from the list
09-12 08:26:08.760  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:26:08.760  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc2f39e removed from the list
09-12 08:26:08.760  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 08:26:08.760  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:26:08.760  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:26:08.761  4344  4363 D BtGatt.ScanManager: handling starting scan
,09-12 08:26:08.761  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-12 08:26:08.761  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.761  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 08:26:08.762  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.762  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.762  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 08:26:08.762  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc2f39e not in the list
09-12 08:26:08.762  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-12 08:26:08.762  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 08:26:08.762  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 08:26:08.762  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 08:26:08.763  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 08:26:08.763  3993  4042 D BluetoothAdapter: STATE_ON
,09-12 08:26:08.764  4344  4354 D BtGatt.GattService: stopScan() - queue size =1
09-12 08:26:08.764  4344  4382 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 08:26:08.765  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 08:26:08.765  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
09-12 08:26:08.765  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 08:26:08.765  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 08:26:08.765  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 08:26:08.766  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 08:26:08.766  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 08:26:08.766  3993  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 08:26:08.766  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 08:26:08.767  4344  4360 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 08:26:08.767  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-12 08:26:08.767  4344  4363 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 08:26:08.767  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.770  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 08:26:08.770  3993  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 08:26:08.770  3993  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 08:26:08.771  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.771  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 08:26:08.771  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.771  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e86e95 removed from the list
,09-12 08:26:08.771  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.771  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.771  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:26:08.771  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.771  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b0e4c removed from the list,
09-12 08:26:08.773  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 08:26:08.773  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82e5f11 added. We now have 2 listener(s)
09-12 08:26:08.773  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 08:26:08.773  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.773  4344  4363 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 08:26:08.773  4344  4363 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 08:26:08.775  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 08:26:08.775  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 08:26:08.775  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 08:26:08.775  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.775  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dbd876 added. We now have 9 listener(s)
,09-12 08:26:08.776  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:08.778  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 08:26:08.787  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 08:26:08.789  4344  4360 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 08:26:08.789  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 08:26:08.794  3993  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 08:26:08.796  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 08:26:08.796  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:26:08.797  3993  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 08:26:08.797  3993  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 08:26:08.798  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 08:26:08.798  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8eadae4 added. We now have 3 listener(s)
09-12 08:26:08.800  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 08:26:08.800  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 08:26:08.800  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 08:26:08.800  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 08:26:08.801  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:26:08.801  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b08db4d added. We now have 10 listener(s)
09-12 08:26:08.801  3993  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 08:26:08.801  3993  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 08:26:08.801  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 08:26:08.802  3993  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 08:26:08.802  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.802  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.802  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 08:26:08.802  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 08:26:08.802  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82e5f11 removed from the list
09-12 08:26:08.802  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.802  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dbd876 removed from the list
09-12 08:26:08.804  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 08:26:08.804  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.804  4344  4363 D BtGatt.ScanManager: stopping BLe Batch
09-12 08:26:08.804  3993  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 08:26:08.804  3993  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-12 08:26:08.805  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.806  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.806  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.808  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.808  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 08:26:08.808  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.808  3993  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dbd876 not in the list
09-12 08:26:08.808  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 08:26:08.808  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 08:26:08.810  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 08:26:08.810  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 08:26:08.810  3993  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 08:26:08.810  3993  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b08db4d removed from the list
09-12 08:26:08.810  3993  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 08:26:08.810  3993  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 08:26:08.811  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 08:26:08.811  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 08:26:08.811  3993  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 08:26:08.811  4344  4363 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 08:26:08.811  3993  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 08:26:08.811  3993  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8eadae4 removed from the list
09-12 08:26:08.812  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 08:26:08.812  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 08:26:08.813  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 08:26:08.813  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 08:26:08.813  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-12 08:26:08.813  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:26:08.817  4344  4360 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 08:26:08.817  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 08:26:08.822  3993  4432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 481, name: My test thread name)
,09-12 08:26:08.822  3993  4432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 481, thread name: My test thread name)
09-12 08:26:08.823  3993  4432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 481, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 08:26:08.825  3993  4433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 483, name: My test thread name)
,09-12 08:26:08.825  3993  4433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 483, thread name: My test thread name)
09-12 08:26:08.825  3993  4433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 483, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 08:26:08.827  3993  4042 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-12 08:26:08.827  3993  4042 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-12 08:26:08.827  3993  4042 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-12 08:26:08.827  3993  4042 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 08:26:08.827  3993  4042 D com.test.thalitest.ThaliTestRunner: Total duration: 22938 ms
09-12 08:26:08.829  3993  4042 I jxcore-log: *Native tests were executed*
09-12 08:26:08.829  3993  4042 I jxcore-log: 
,09-12 08:26:08.829  3993  4042 I jxcore-log: Total number of executed tests:  80
09-12 08:26:08.829  3993  4042 I jxcore-log: 
09-12 08:26:08.829  3993  4042 I jxcore-log: Number of passed tests:  80
09-12 08:26:08.829  3993  4042 I jxcore-log: 
,09-12 08:26:08.830  3993  4042 I jxcore-log: Number of failed tests:  0
09-12 08:26:08.830  3993  4042 I jxcore-log: 
09-12 08:26:08.830  3993  4042 I jxcore-log: Number of ignored tests:  0
09-12 08:26:08.830  3993  4042 I jxcore-log: 
,09-12 08:26:08.830  3993  4042 I jxcore-log: Total duration:  22938
09-12 08:26:08.830  3993  4042 I jxcore-log: 
,09-12 08:26:08.832  3993  4042 I jxcore-log: Unit Test app is loaded
09-12 08:26:08.832  3993  4042 I jxcore-log: 
,09-12 08:26:08.843  3993  3993 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 08:26:08.845  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.845  3993  4042 I jxcore-log: 
,09-12 08:26:08.851  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.851  3993  4042 I jxcore-log: 
,09-12 08:26:08.853  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.853  3993  4042 I jxcore-log: 
,09-12 08:26:08.853  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.853  3993  4042 I jxcore-log: 
,09-12 08:26:08.854  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-12 08:26:08.854  3993  4042 I jxcore-log: 
,09-12 08:26:08.855  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.855  3993  4042 I jxcore-log: 
,09-12 08:26:08.857  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.857  3993  4042 I jxcore-log: 
,09-12 08:26:08.859  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.859  3993  4042 I jxcore-log: 
,09-12 08:26:08.859  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.859  3993  4042 I jxcore-log: 
,09-12 08:26:08.860  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.860  3993  4042 I jxcore-log: 
,09-12 08:26:08.861  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 08:26:08.861  3993  4042 I jxcore-log: 
,09-12 08:26:08.862  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.862  3993  4042 I jxcore-log: 
,09-12 08:26:08.862  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.862  3993  4042 I jxcore-log: 
,09-12 08:26:08.863  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.863  3993  4042 I jxcore-log: 
,09-12 08:26:08.864  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.864  3993  4042 I jxcore-log: 
,09-12 08:26:08.864  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.864  3993  4042 I jxcore-log: 
,09-12 08:26:08.865  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.865  3993  4042 I jxcore-log: 
,09-12 08:26:08.866  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.866  3993  4042 I jxcore-log: 
,09-12 08:26:08.866  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.866  3993  4042 I jxcore-log: 
,09-12 08:26:08.867  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.867  3993  4042 I jxcore-log: 
,09-12 08:26:08.867  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.867  3993  4042 I jxcore-log: 
,09-12 08:26:08.868  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.868  3993  4042 I jxcore-log: 
,09-12 08:26:08.868  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.868  3993  4042 I jxcore-log: 
,09-12 08:26:08.870  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.870  3993  4042 I jxcore-log: 
,09-12 08:26:08.870  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 08:26:08.870  3993  4042 I jxcore-log: 
,09-12 08:26:08.871  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.871  3993  4042 I jxcore-log: 
,09-12 08:26:08.872  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 08:26:08.872  3993  4042 I jxcore-log: 
,09-12 08:26:08.873  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.873  3993  4042 I jxcore-log: 
,09-12 08:26:08.873  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.873  3993  4042 I jxcore-log: 
,09-12 08:26:08.874  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.874  3993  4042 I jxcore-log: 
09-12 08:26:08.875  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.875  3993  4042 I jxcore-log: 
,09-12 08:26:08.875  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.875  3993  4042 I jxcore-log: 
,09-12 08:26:08.876  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 08:26:08.876  3993  4042 I jxcore-log: 
,09-12 08:26:08.880  3993  4042 I jxcore-log: My device name is: motorola-Nexus 6
09-12 08:26:08.880  3993  4042 I jxcore-log: 
,09-12 08:26:09.152  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 08:26:09.220  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 08:26:09.270  3993  3993 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 08:26:10.199   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-12 08:26:12.004  1912  2799 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 08:26:12.795  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:12.906  1520  4436 I VacuumService: Vacuum at: now=1473661572906 tag=VacuumService
,09-12 08:26:12.907  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:12.914  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-12 08:26:12.914  3993  4042 I jxcore-log: 
,09-12 08:26:12.920  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 08:26:12.922  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:12.956  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 08:26:12.956  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 08:26:12.956  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:12.956  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:12.971  3686  3686 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 08:26:12.972  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 08:26:12.972  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 08:26:13.016  1520  4437 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 08:26:13.017  1520  4437 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 08:26:13.041  1520  4437 W Uploader:  no longer exists, so no auth token.
,09-12 08:26:13.898  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-12 08:26:13.898  3993  4042 I jxcore-log: 
,09-12 08:26:13.926  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-12 08:26:13.926  3993  4042 I jxcore-log: 
,09-12 08:26:13.931  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-12 08:26:13.931  3993  4042 I jxcore-log: 
,09-12 08:26:13.950  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-12 08:26:13.950  3993  4042 I jxcore-log: 
,09-12 08:26:13.955  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-12 08:26:13.955  3993  4042 I jxcore-log: 
,09-12 08:26:14.373  1520  4437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 08:26:14.373  1520  4437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 08:26:14.373  1520  4437 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:26:14.373  1520  4437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:14.396  1520  4437 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 08:26:14.396  1520  4437 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 08:26:14.396  1520  4437 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 08:26:14.815  1520  4437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 08:26:14.815  1520  4437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.,
09-12 08:26:14.815  1520  4437 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:14.816  1520  4437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:14.852  1520  4437 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 08:26:14.852  1520  4437 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 08:26:14.852  1520  4437 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 08:26:15.263  1520  4437 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 08:26:15.263  1520  4437 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 08:26:15.263  1520  4437 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:26:15.264  1520  4437 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:15.302  1520  4437 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 08:26:15.302  1520  4437 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 08:26:15.302  1520  4437 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 08:26:15.529   872  1309 D ConnectivityService: handlePromptUnvalidated 102
,09-12 08:26:17.173  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-12 08:26:17.173  3993  4042 I jxcore-log: 
,09-12 08:26:17.185  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-12 08:26:17.185  3993  4042 I jxcore-log: 
,09-12 08:26:17.194  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-12 08:26:17.194  3993  4042 I jxcore-log: 
,09-12 08:26:17.350  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-12 08:26:17.350  3993  4042 I jxcore-log: 
,09-12 08:26:18.127  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-12 08:26:18.127  3993  4042 I jxcore-log: 
,09-12 08:26:18.374  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-12 08:26:18.374  3993  4042 I jxcore-log: 
,09-12 08:26:18.381  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-12 08:26:18.381  3993  4042 I jxcore-log: 
,09-12 08:26:18.570  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-12 08:26:18.570  3993  4042 I jxcore-log: 
,09-12 08:26:18.591  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-12 08:26:18.591  3993  4042 I jxcore-log: 
,09-12 08:26:18.596  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-12 08:26:18.596  3993  4042 I jxcore-log: 
,09-12 08:26:18.602  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-12 08:26:18.602  3993  4042 I jxcore-log: 
,09-12 08:26:18.617  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-12 08:26:18.617  3993  4042 I jxcore-log: 
,09-12 08:26:18.636  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-12 08:26:18.636  3993  4042 I jxcore-log: 
,09-12 08:26:18.720  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-12 08:26:18.720  3993  4042 I jxcore-log: 
,09-12 08:26:18.726  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-12 08:26:18.726  3993  4042 I jxcore-log: 
,09-12 08:26:18.752  3993  4042 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-12 08:26:18.752  3993  4042 I jxcore-log: 
,09-12 08:26:18.765  3993  4042 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 08:26:18.766  3993  4042 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-12 08:26:18.766  3993  4042 I jxcore-log: 
,09-12 08:26:18.769  3993  4042 I jxcore-log: thaliTape.begin
09-12 08:26:18.769  3993  4042 I jxcore-log: 
,09-12 08:26:18.817  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 08:26:18.817  3993  4042 I jxcore-log: 
,09-12 08:26:18.818  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 08:26:18.818  3993  4042 I jxcore-log: 
09-12 08:26:18.818  3993  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 08:26:18.818  3993  4042 I jxcore-log: 
09-12 08:26:18.819  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 08:26:18.819  3993  4042 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-12 08:26:18.819  3993  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 08:26:18.819  3993  4042 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-12 08:26:35.196  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:35.213  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:35.218  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:26:35.297  1520  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 08:26:35.297  1520  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 08:26:35.297  1520  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:35.298  1520  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:35.351  3686  3686 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 08:26:35.353  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 08:26:35.354  3686  3686 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 08:26:37.674  3921  4450 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 08:26:37.715  3921  4452 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 08:26:37.744  3931  4451 V KeepSync: Connecting to GoogleApiClient
,09-12 08:26:37.747   872  1965 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 08:26:37.806  1520  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:26:37.806  1520  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 08:26:37.806  1520  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:26:37.807  1520  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:37.888  1520  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:26:37.888  1520  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 08:26:37.888  1520  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:37.889  1520  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:37.896  1520  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 08:26:37.896  1520  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 08:26:37.896  1520  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:37.896  1520  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:37.923  3921  4452 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 08:26:37.925  3921  4450 E BooksSync: Soft error
09-12 08:26:37.925  3921  4450 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:26:37.925  3921  4450 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 08:26:37.925  3921  4450 E BooksSync: Sync error
09-12 08:26:37.925  3921  4450 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:26:37.925  3921  4450 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 08:26:37.925  3921  4450 I BooksSync: Finished books sync
09-12 08:26:37.927  1725  4453 V BaseAuthAsyncOperation: access token request failed
09-12 08:26:37.928  3931  4451 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 08:26:37.944   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162557, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:26:38.018  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 08:26:38.019  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 08:26:38.019  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:26:38.020  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:38.082  3931  4451 E KeepSync: IOException
09-12 08:26:38.082  3931  4451 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 08:26:38.082  3931  4451 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:26:38.082  3931  4451 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 08:26:38.082  3931  4451 E KeepSync: 	... 10 more
,09-12 08:26:38.082  3931  4451 W KeepSync: Sync result 2
,09-12 08:26:38.097   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 164584, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:26:38.131  1520  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:26:38.131  1520  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:26:38.131  1520  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:38.131  1520  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:38.148  3724  4455 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 08:26:38.148  3724  4455 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at blb.a(PG:3937)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at czp.a(PG:18188)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:26:38.148  3724  4455 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	... 12 more
09-12 08:26:38.148  3724  4455 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at fal.a(PG:38)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:26:38.148  3724  4455 E HttpOperation: 	... 14 more
,09-12 08:26:38.187  1520  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:26:38.187  1520  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:26:38.187  1520  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:26:38.187  1520  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:26:38.206  3724  4455 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 08:26:38.206  3724  4455 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at hec.a(PG:42)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at hee.a(PG:102)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at czr.a(PG:65)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at kka.a(PG:108)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at czp.a(PG:19176)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:26:38.206  3724  4455 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	... 15 more
09-12 08:26:38.206  3724  4455 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at fal.a(PG:38)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:26:38.206  3724  4455 E HttpOperation: 	... 17 more
,09-12 08:26:38.206  3724  4455 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 08:26:38.206  3724  4455 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at hec.a(PG:42)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at hee.a(PG:102)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at czr.a(PG:65)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at kka.a(PG:108)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	... 15 more
09-12 08:26:38.206  3724  4455 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at fal.a(PG:38)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 08:26:38.206  3724  4455 E ExperimentLoader: 	... 17 more
,09-12 08:26:38.366   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 169294, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:26:41.294  1520  2079 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 08:26:58.680   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:27:03.637  1878  1929 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-12 08:27:03.637  1878  1929 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 08:27:03.670  1520  1520 I ConfigService: onCreate
,09-12 08:27:08.745  1520  1520 I ConfigService: onDestroy
,09-12 08:27:08.836  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:27:08.849  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:27:08.851  3931  4461 V KeepSync: Connecting to GoogleApiClient
09-12 08:27:08.851   872  2226 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 08:27:08.938  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:27:08.938  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:27:08.938  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:27:08.939  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:27:08.958  3724  4460 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 08:27:08.958  3724  4460 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at blb.a(PG:3937)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at czp.a(PG:18188)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:27:08.958  3724  4460 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	... 12 more
09-12 08:27:08.958  3724  4460 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at fal.a(PG:38)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:27:08.958  3724  4460 E HttpOperation: 	... 14 more
,09-12 08:27:09.020  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 08:27:09.020  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 08:27:09.020  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:27:09.020  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-12 08:27:09.084  1520  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:27:09.084  1520  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:27:09.084  1520  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:27:09.084  1520  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:27:09.113  1725  4464 V BaseAuthAsyncOperation: access token request failed
,09-12 08:27:09.116  3931  4461 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 08:27:09.130  3724  4460 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 08:27:09.130  3724  4460 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at hec.a(PG:42)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at hee.a(PG:102)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at czr.a(PG:65)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at kka.a(PG:108)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at czp.a(PG:19176)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:27:09.130  3724  4460 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	... 15 more
09-12 08:27:09.130  3724  4460 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at fal.a(PG:38)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:27:09.130  3724  4460 E HttpOperation: 	... 17 more
,09-12 08:27:09.131  3724  4460 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 08:27:09.131  3724  4460 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at hec.a(PG:42)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at hee.a(PG:102),
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at czr.a(PG:65)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at kka.a(PG:108)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	... 15 more
09-12 08:27:09.131  3724  4460 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	,at fal.a(PG:38)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 08:27:09.131  3724  4460 E ExperimentLoader: 	... 17 more
,09-12 08:27:09.202  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 08:27:09.202  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 08:27:09.202  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:27:09.202  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:27:09.222  3931  4461 E KeepSync: IOException
09-12 08:27:09.222  3931  4461 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 08:27:09.222  3931  4461 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:27:09.222  3931  4461 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 08:27:09.222  3931  4461 E KeepSync: 	... 10 more
,09-12 08:27:09.222  3931  4461 W KeepSync: Sync result 2
,09-12 08:27:09.235   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 215139, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:27:09.279   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 215087, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:27:09.289  3921  4466 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 08:27:09.302  3921  4467 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 08:27:09.323  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:27:09.324  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 08:27:09.324  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:27:09.324  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:27:09.359  1520  4463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:27:09.359  1520  4463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 08:27:09.359  1520  4463 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:27:09.359  1520  4463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:27:09.371  3921  4467 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 08:27:09.371  3921  4466 E BooksSync: Soft error
09-12 08:27:09.371  3921  4466 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:27:09.371  3921  4466 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 08:27:09.372  3921  4466 E BooksSync: Sync error
09-12 08:27:09.372  3921  4466 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:27:09.372  3921  4466 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 08:27:09.372  3921  4466 I BooksSync: Finished books sync
,09-12 08:27:09.382   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215418, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:28:00.841   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:28:09.599  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:28:09.601  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:28:09.637  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:28:09.637  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 08:28:09.637  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:28:09.638  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:28:09.663  3724  4471 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 08:28:09.663  3724  4471 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at blb.a(PG:3937)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at czp.a(PG:18188)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:28:09.663  3724  4471 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	... 12 more
09-12 08:28:09.663  3724  4471 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at fal.a(PG:38)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:28:09.663  3724  4471 E HttpOperation: 	... 14 more
,09-12 08:28:09.728  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:28:09.728  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:28:09.729  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:28:09.729  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:28:09.745  3724  4471 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 08:28:09.745  3724  4471 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at hec.a(PG:42)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at hee.a(PG:102)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at czr.a(PG:65)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at kka.a(PG:108)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at czp.a(PG:19176)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:28:09.745  3724  4471 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	... 15 more
09-12 08:28:09.745  3724  4471 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at fal.a(PG:38)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:28:09.745  3724  4471 E HttpOperation: 	... 17 more
,09-12 08:28:09.746  3724  4471 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 08:28:09.746  3724  4471 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at hec.a(PG:42)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at hee.a(PG:102)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at czr.a(PG:65)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at kka.a(PG:108)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	... 15 more
09-12 08:28:09.746  3724  4471 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at fal.a(PG:38)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 08:28:09.746  3724  4471 E ExperimentLoader: 	... 17 more
,09-12 08:28:09.868   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 276015, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:28:39.969  3921  4479 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 08:28:40.021  3921  4480 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 08:28:40.043  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:28:40.045  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:28:40.042  3931  4478 V KeepSync: Connecting to GoogleApiClient
,09-12 08:28:40.049   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 08:28:40.101  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:28:40.101  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 08:28:40.101  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:28:40.102  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:28:40.162  1520  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 08:28:40.162  1520  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 08:28:40.162  1520  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:28:40.162  1520  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:28:40.163  1520  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 08:28:40.163  1520  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 08:28:40.163  1520  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:28:40.163  1520  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:28:40.187  3921  4480 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:28:40.188  3921  4479 E BooksSync: Soft error
09-12 08:28:40.188  3921  4479 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:28:40.188  3921  4479 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 08:28:40.188  3921  4479 E BooksSync: Sync error
09-12 08:28:40.188  3921  4479 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:28:40.188  3921  4479 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 08:28:40.188  3921  4479 I BooksSync: Finished books sync
,09-12 08:28:40.199  1725  4481 V BaseAuthAsyncOperation: access token request failed
,09-12 08:28:40.205   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277630, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:28:40.208  3931  4478 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 08:28:40.276  1520  4463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 08:28:40.277  1520  4463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 08:28:40.277  1520  4463 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:28:40.277  1520  4463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:28:40.300  3931  4478 E KeepSync: IOException
09-12 08:28:40.300  3931  4478 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 08:28:40.300  3931  4478 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:28:40.300  3931  4478 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 08:28:40.300  3931  4478 E KeepSync: 	... 10 more
,09-12 08:28:40.301  3931  4478 W KeepSync: Sync result 2
,09-12 08:28:40.309   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 276615, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:28:44.387   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:28:57.667   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:29:17.502  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:29:17.511  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:29:17.515  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:29:17.538  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 08:29:17.538  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 08:29:17.538  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:29:17.539  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:29:17.575  1520  1532 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 08:29:17.575  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 08:29:17.575  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 08:29:17.575  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 08:29:17.575  1520  1532 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 08:29:17.575  1520  1532 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 08:29:17.575  1520  1532 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 08:29:17.579  3686  3716 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 08:29:17.579  3686  3716 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 08:29:17.579  3686  3716 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 08:29:17.579  3686  3716 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 08:29:17.579  3686  3716 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 08:29:17.579  3686  3716 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 08:29:17.579  3686  3716 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 08:30:02.254   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:30:09.994   872   872 I ActivityManager: Start proc 4490:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-12 08:30:10.071  4490  4490 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-12 08:30:10.099  4490  4490 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-12 08:30:10.099  4490  4490 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 08:30:10.099  4490  4490 I GAv4    :   adb logcat -s GAv4
,09-12 08:30:10.117  4490  4490 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 08:30:10.124  4490  4490 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 08:30:10.137  4490  4505 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 08:30:10.247  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:30:10.249  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:30:10.279  1520  4463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:30:10.279  1520  4463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:30:10.279  1520  4463 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:30:10.279  1520  4463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:30:10.299  3724  4507 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 08:30:10.299  3724  4507 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at blb.a(PG:3937)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at czp.a(PG:18188)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:30:10.299  3724  4507 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	... 12 more
09-12 08:30:10.299  3724  4507 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at fal.a(PG:38)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:30:10.299  3724  4507 E HttpOperation: 	... 14 more
,09-12 08:30:10.339  1520  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 08:30:10.339  1520  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 08:30:10.339  1520  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:30:10.340  1520  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:30:10.358  3724  4507 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 08:30:10.358  3724  4507 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jdm.a(PG:82)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jcs.o(PG:406)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jcn.a(PG:1379)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jcs.i(PG:143)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at hec.a(PG:42)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at hee.a(PG:102)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at czr.a(PG:65)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at kka.a(PG:108)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at czp.a(PG:19176)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at czp.a(PG:9081)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at czq.run(PG:1686)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:30:10.358  3724  4507 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jdj.a(PG:4091)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jdj.a(PG:1125)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jdm.a(PG:77)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	... 15 more
09-12 08:30:10.358  3724  4507 E HttpOperation: Caused by: faj: BadAuthentication
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at fal.a(PG:38)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	at jdj.a(PG:4089)
09-12 08:30:10.358  3724  4507 E HttpOperation: 	... 17 more
,09-12 08:30:10.358  3724  4507 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 08:30:10.358  3724  4507 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at hec.a(PG:42)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at hee.a(PG:102)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at czr.a(PG:65)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at kka.a(PG:108)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	... 15 more
09-12 08:30:10.358  3724  4507 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at fal.a(PG:38)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 08:30:10.358  3724  4507 E ExperimentLoader: 	... 17 more
,09-12 08:30:10.453   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 396636, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:30:10.453   872  1701 I ActivityManager: Killing 3861:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 08:30:12.854   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=399557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:30:40.338  1520  2079 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 08:30:41.799  3931  4510 V KeepSync: Connecting to GoogleApiClient
,09-12 08:30:41.800   872  1701 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 08:30:41.839  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:30:41.841  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:30:41.877  1520  2276 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 08:30:41.877  1520  2276 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-12 08:30:41.878  1520  2276 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:30:41.878  1520  2276 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:30:41.903  1725  4511 V BaseAuthAsyncOperation: access token request failed
,09-12 08:30:41.904  3931  4510 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 08:30:41.969  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 08:30:41.969  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 08:30:41.969  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 08:30:41.969  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:30:41.999  3931  4510 E KeepSync: IOException
09-12 08:30:41.999  3931  4510 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 08:30:41.999  3931  4510 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 08:30:41.999  3931  4510 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 08:30:41.999  3931  4510 E KeepSync: 	... 10 more
09-12 08:30:41.999  3931  4510 W KeepSync: Sync result 2
,09-12 08:30:42.012   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 428366, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:31:02.534   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:31:12.206  3921  4513 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 08:31:12.249  3921  4514 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 08:31:12.269  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:31:12.274  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:31:12.327  1520  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:31:12.328  1520  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 08:31:12.328  1520  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:31:12.328  1520  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:31:12.380  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:31:12.384  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 08:31:12.430  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 08:31:12.430  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 08:31:12.431  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 08:31:12.431  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 08:31:12.462  3921  4514 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 08:31:12.464  3921  4513 E BooksSync: Soft error
09-12 08:31:12.464  3921  4513 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:31:12.464  3921  4513 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 08:31:12.464  3921  4513 E BooksSync: Sync error
09-12 08:31:12.464  3921  4513 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 08:31:12.464  3921  4513 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 08:31:12.464  3921  4513 I BooksSync: Finished books sync
,09-12 08:31:12.476   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 429989, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 08:31:12.680   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=459383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:31:56.067   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=502771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:32:01.641   872  1296 I PowerManagerService: Waking up from dozing (uid 1000)...
,09-12 08:32:01.642   872   872 V KeyguardServiceDelegate: onStartedWakingUp()
09-12 08:32:01.643   872   892 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,09-12 08:32:01.651  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-12 08:32:01.655   872   892 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@b6cfb45)
,09-12 08:32:01.657  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 08:32:01.657  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-12 08:32:01.662   280   280 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
,09-12 08:32:01.662   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,09-12 08:32:01.672   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
09-12 08:32:01.677   872  2005 V KeyguardServiceDelegate: **** SHOWN CALLED ****
09-12 08:32:01.678   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:32:01.686   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:01.688   872  1307 E native  : do suspend false
,09-12 08:32:01.689  1912  1912 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,09-12 08:32:01.693  1939  2088 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,09-12 08:32:01.693  1939  2088 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
09-12 08:32:01.694  1939  2088 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
09-12 08:32:01.694  1939  2066 D BrcmNfcJni: RoutingManager::commitRouting
09-12 08:32:01.694  1939  2088 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,09-12 08:32:01.697   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 08:32:01.701  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 08:32:01.701  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-12 08:32:01.712   872  1389 I ActivityManager: Start proc 4518:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,09-12 08:32:01.757  4518  4518 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,09-12 08:32:01.771   375  1471 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-12 08:32:01.771   375  1471 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 08:32:01.772   872   892 I DisplayPowerController: Unblocked screen on after 129 ms
,09-12 08:32:01.773   872   892 V KeyguardServiceDelegate: onScreenTurnedOn()
09-12 08:32:01.773   872   892 I DreamManagerService: Gently waking up from dream.
,09-12 08:32:01.775   872  1969 I DreamManagerService: Leaving dreamland.
09-12 08:32:01.775   872  1700 I ActivityManager: Killing 3786:com.android.defcontainer/u0a7 (adj 15): empty #17
09-12 08:32:01.776   872   887 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 08:32:01.815  1939  2350 D NfcService: Discovery configuration equal, not updating.
,09-12 08:32:01.914   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,09-12 08:32:01.914   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,09-12 08:32:01.916   872  1330 D SurfaceControl: Excessive delay in setPowerMode(): 254ms
,09-12 08:32:04.715   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:04.720   872  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-12 08:32:06.694   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:32:13.805   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:16.841   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:47.187   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:50.147   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=556850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:32:50.218   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:53.254   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:32:56.297   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:33:01.665  1878  1929 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-12 08:33:01.667  1878  1929 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 08:33:01.717  1520  1520 I ConfigService: onCreate
,09-12 08:33:06.811  1520  1520 I ConfigService: onDestroy
,09-12 08:33:20.572   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:33:23.601   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 08:33:24.040   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:34:01.732  1912  2799 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 08:34:02.638   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 08:34:02.648  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-12 08:34:03.168  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 08:34:03.168  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 08:34:03.203   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 08:34:03.209  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6f56f7e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9631716, 16908290=android.view.AbsSavedState$1@9631716}, android:focusedViewId=100}]}]
,09-12 08:34:03.209  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 08:34:03.213  3993  3993 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 08:34:03.213  3993  3993 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 08:34:03.216   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 08:34:03.216   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-12 08:34:03.217   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-12 08:34:03.446   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 08:34:03.449   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 08:34:03.452   872  1330 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,09-12 08:34:03.457   872   892 I DreamManagerService: Entering dreamland.
,09-12 08:34:03.458   872   892 I PowerManagerService: Dozing...
,09-12 08:34:03.460   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 08:34:03.512   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 08:34:03.521   872  1307 E native  : do suspend true
,09-12 08:34:03.650   375  1472 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 08:34:03.650   375  1472 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 08:34:07.373   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=634077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:34:23.920   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 08:35:02.688  1878  1929 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-12 08:35:02.689  1878  1929 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 08:35:02.743  1520  1520 I ConfigService: onCreate
,09-12 08:35:07.320   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=694023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:35:07.816  1520  1520 I ConfigService: onDestroy
,09-12 08:41:08.026  1725  4579 I EventLogService: Opted in for usage reporting
,09-12 08:41:08.027  1725  4579 I EventLogService: Aggregate from 1473660605167 (log), 1473660605167 (data)
,09-12 08:41:08.083  1725  4579 W EventLogAggregator: Unknown tag: snet_gcore
09-12 08:41:08.083  1725  4579 W EventLogAggregator: Unknown tag: snet_launch_service
,09-12 08:41:08.217  1725  4579 I ServiceDumpSys: dumping service [account]
,09-12 08:41:13.000   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 08:41:19.880   872  4408 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1066583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 08:43:51.560   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-12 08:49:03.876  4603  4603 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 08:49:03.881  4603  4603 D AndroidRuntime: CheckJNI is OFF
09-12 08:49:03.917  4603  4603 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 08:49:03.958  4603  4603 I Radio-JNI: register_android_hardware_Radio DONE
09-12 08:49:03.978  4603  4603 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 08:49:03.988   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-12 08:49:03.989   872   885 I ActivityManager: Killing 3993:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-12 08:49:04.101   872   895 W PackageSettings: Skipping PackageSetting{b48cd77 com.example.hello/10273} due to missing metadata
09-12 08:49:04.129   872  1992 D GraphicsStats: Buffer count: 2
09-12 08:49:04.129   872  2005 I WindowState: WIN DEATH: Window{4fd02a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 08:49:04.131   872  1308 D WifiService: Client connection lost with reason: 4
09-12 08:49:04.132   872   895 I art     : Starting a blocking GC Explicit
09-12 08:49:04.165   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-12 08:49:04.166   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 08:49:04.171   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-12 08:49:04.171   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 08:49:04.171   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.171   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.171   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.171   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 08:49:04.173   872   885 I ActivityManager:   Force finishing activity ActivityRecord{25383a9 u0 com.test.thalitest/.MainActivity t4}
09-12 08:49:04.198   872  2228 W ActivityManager: Spurious death for ProcessRecord{afef0f0 0:com.test.thalitest/u0a0}, curProc for 3993: null
09-12 08:49:04.201   872   895 I art     : Explicit concurrent mark sweep GC freed 31235(2MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 1.416ms total 67.697ms
09-12 08:49:04.221   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 08:49:04.223  4603  4603 I art     : System.exit called, status: 0
09-12 08:49:04.224  4603  4603 I AndroidRuntime: VM exiting with result code 0.
09-12 08:49:04.276   872   895 I ActivityManager: Start proc 4616:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-12 08:49:04.283   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 08:49:04.293   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 08:49:04.298  4344  4344 D BluetoothMapAppObserver: onReceive
09-12 08:49:04.298  4344  4344 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-12 08:49:04.305  3808  3808 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 08:49:04.308   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 08:49:04.312  1912  2304 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 08:49:04.318  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 08:49:04.340   872  2228 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3993 uid 10000
09-12 08:49:04.341  1878  1878 I Keyboard.Facilitator: onFinishInput()
09-12 08:49:04.348  1878  4631 I Keyboard.Facilitator.DecoderInitializer: run()
09-12 08:49:04.351   872  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-12 08:49:04.365  1878  4631 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 08:49:04.365  1878  4631 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 08:49:04.365  1878  4631 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 08:49:04.365  1878  4631 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 08:49:04.366  1953  1953 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-12 08:49:04.368  1878  4631 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 08:49:04.368  1878  4631 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 08:49:04.369  1878  4631 I Decoder : createOrResetDecoder
09-12 08:49:04.378   872  1389 I ActivityManager: Start proc 4633:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-12 08:49:04.390   872  1968 I ActivityManager: Killing 2027:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-12 08:49:04.400   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 08:49:04.427   872  1308 D WifiService: Client connection lost with reason: 4
09-12 08:49:04.440  1520  1520 I ConfigService: onCreate
09-12 08:49:04.447  4633  4633 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 08:49:04.453  1520  4645 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 08:49:04.453  1520  4645 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-12 08:49:04.455  1520  4645 W SQLiteOpenHelper: Opened config.db in read-only mode
09-12 08:49:04.471  1878  4631 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-12 08:49:04.495  1878  4631 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 08:49:04.496  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-12 08:49:04.496  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 08:49:04.498  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-12 08:49:04.498  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 08:49:04.499  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 08:49:04.499  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-12 08:49:04.500  1878  4631 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 08:49:04.500  1878  4631 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 08:49:04.500  1878  4631 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-12 08:49:04.500  1878  4631 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-12 08:49:04.500  1878  4631 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 08:49:04.500  1878  4631 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-12 08:49:04.514  4633  4633 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.521  4633  4648 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.521  4633  4648 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.527  4633  4650 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 08:49:04.549  4633  4648 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.553  4633  4650 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
09-12 08:49:04.554  4633  4650 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 08:49:04.554  4633  4650 E AndroidRuntime: Process: android.process.acore, PID: 4633
09-12 08:49:04.554  4633  4650 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.554  4633  4650 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.555  4633  4648 I Process : Sending signal. PID: 4633 SIG: 9
09-12 08:49:04.558   872  1701 I ActivityManager: Start proc 4651:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-12 08:49:04.559   278   278 E lowmemorykiller: Error writing /proc/4633/oom_score_adj; errno=22
09-12 08:49:04.564  1970  2050 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 08:49:04.566   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-12 08:49:04.567   872   884 E PackageManager: Failed to write settings, restoring backup
09-12 08:49:04.567   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 08:49:04.567   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 08:49:04.567   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 08:49:04.567   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 08:49:04.567   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 08:49:04.567   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.567   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.567   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: Can't write: system_app_crash
09-12 08:49:04.567   872  4657 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 08:49:04.567   872  4657 E DropBoxManagerService: 	... 5 more
09-12 08:49:04.569   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-12 08:49:04.569   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 08:49:04.569   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 08:49:04.569   872   885 E DropBoxManagerService: 	... 13 more
09-12 08:49:04.580   872  1994 I ActivityManager: Start proc 4664:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-12 08:49:04.581  1970  2050 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 08:49:04.581  1970  2050 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1970
09-12 08:49:04.581  1970  2050 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.581  1970  2050 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: Can't write: system_app_crash
09-12 08:49:04.585   872  4669 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 08:49:04.585   872  4669 E DropBoxManagerService: 	... 5 more
09-12 08:49:04.585   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 08:49:04.590  1970  2050 I Process : Sending signal. PID: 1970 SIG: 9
09-12 08:49:04.606  4651  4651 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-12 08:49:04.640  1520  1520 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-12 08:49:04.642   278   278 E lowmemorykiller: Error writing /proc/4633/oom_score_adj; errno=22
09-12 08:49:04.643   278   278 E lowmemorykiller: Error writing /proc/4633/oom_score_adj; errno=22
09-12 08:49:04.643  1520  1520 D AndroidRuntime: Shutting down VM
09-12 08:49:04.644  1520  1520 E AndroidRuntime: FATAL EXCEPTION: main
09-12 08:49:04.644  1520  1520 E AndroidRuntime: Process: com.google.process.gapps, PID: 1520
09-12 08:49:04.644  1520  1520 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 08:49:04.644  1520  1520 E AndroidRuntime: 	... 8 more
09-12 08:49:04.647  1520  1520 I Process : Sending signal. PID: 1520 SIG: 9
09-12 08:49:04.648   872  4682 E DropBoxManagerService: Can't write: system_app_crash
09-12 08:49:04.648   872  4682 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 08:49:04.648   872  4682 E DropBoxManagerService: 	... 5 more
09-12 08:49:04.648   278   278 E lowmemorykiller: Error writing /proc/4633/oom_score_adj; errno=22
09-12 08:49:04.689   278   278 E lowmemorykiller: Error writing /proc/4633/oom_score_adj; errno=22
09-12 08:49:04.696   872  1994 I ActivityManager: Killing 4059:com.android.settings/1000 (adj 15): empty #17

```
